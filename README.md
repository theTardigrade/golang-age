# age

```golang
const day, month, year = 27, 5, 1960

date := time.Date(year, month, day, 0, 0, 0, 0, time.UTC)
dateAge := age.Calculate(date)
```