# MGL Language Reference

## Reading Data
```mgl
data = read("users.csv")
```

## Filtering
```mgl
adults = data.filter(age > 18)
uk = data.filter(country == "UK")
```

## Transforming
```mgl
result = data.map(row -> { name: row.name, total: row.qty * row.price })
```

## Aggregation
```mgl
print(data.group_by(country).sum(revenue))
```

## Functions
```mgl
fn classify(x) {
    if (x > 100) { return "high" }
    return "low"
}
```

See full reference in the IDE Docs page.