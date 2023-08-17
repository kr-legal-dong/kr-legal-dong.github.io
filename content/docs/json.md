---
title: JSON
type: docs
---

# JSON

## Url

### 시
```
https://kr-legal-dong.github.io/data/si.json
```

### 구
```
https://kr-legal-dong.github.io/data/gu.json
```

### 동
```
https://kr-legal-dong.github.io/data/dong.json
```

### 상세
```
https://kr-legal-dong.github.io/data/detail.json
```


## Model

### 시
```go
type Si struct {
	Code   string `json:"code"`
	Name   string `json:"name"`
	Active bool   `json:"active"`
}
```

### 구

```go
type Gu struct {
	Code     string `json:"code"`
	SiCode   string `json:"siCode"`
	SiName   string `json:"siName"`
	FullName string `json:"fullName"`
	Name     string `json:"name"`
	Active   bool   `json:"active"`
}
```

### 동

```go
type Dong struct {
	Code     string `json:"code"`
	SiCode   string `json:"siCode"`
	SiName   string `json:"siName"`
	GuCode   string `json:"guCode"`
	GuName   string `json:"guName"`
	FullName string `json:"fullName"`
	Name     string `json:"name"`
	Active   bool   `json:"active"`
}
```

### 상세

```go
type Detail struct {
	Code     string `json:"code"`
	SiCode   string `json:"siCode"`
	SiName   string `json:"siName"`
	GuCode   string `json:"guCode"`
	GuName   string `json:"guName"`
	DongCode string `json:"dongCode"`
	DongName string `json:"dongName"`
	FullName string `json:"fullName"`
	Name     string `json:"name"`
	Active   bool   `json:"active"`
}
```