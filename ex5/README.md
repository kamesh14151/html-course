# Exercise 5 – Tables ⭐⭐

## 🎯 What You Will Learn
- How to create a basic table
- Table headers vs data cells
- Merging cells with colspan / rowspan
- Using thead, tbody, tfoot

---

## 📖 Explanation

### Basic Table Structure
```html
<table>
  <tr>
    <th>Header</th>
  </tr>
  <tr>
    <td>Data</td>
  </tr>
</table>
```

### Merging Cells
```html
<!-- colspan: merge 2 columns into 1 -->
<td colspan="2">Spans two columns</td>

<!-- rowspan: merge 2 rows into 1 -->
<td rowspan="2">Spans two rows</td>
```

### Table Sections
```html
<table>
  <thead> <!-- header rows --> </thead>
  <tbody> <!-- main data rows --> </tbody>
  <tfoot> <!-- footer/totals --> </tfoot>
</table>
```

| Tag | Meaning |
|-----|---------|
| `<table>` | Creates the table |
| `<tr>` | Table Row |
| `<th>` | Header cell (bold) |
| `<td>` | Data cell |
| `<thead>` | Header section |
| `<tbody>` | Body section |
| `<tfoot>` | Footer section |

---

## ✅ Your Task

1. Create a timetable table (Mon–Fri rows, 3 subject columns)
2. Add a tfoot row showing "Total: 15 classes"
3. Try `colspan` to merge the header row
