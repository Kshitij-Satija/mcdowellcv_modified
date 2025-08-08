# McDowell CV — Modified Versions (`mcdowellcv_2`, `_3`, `_4`)

This is a modified and modernized fork of the original **McDowell CV** LuaLaTeX class, originally created by [Daniil Belyakov](https://github.com/dnl-blkv), based on the resume design proposed by Gayle L. McDowell at [CareerCup](http://www.careercup.com/resume).

These modified templates are designed specifically for **modern academic and technical resumes**, especially for:
- Undergraduate/graduate students
- Internships and research applications
- ATS-friendly and hyperlinked resumes

---

## ✨ What's New in This Fork?

All variants support:
- ⚡ FontAwesome-based contact header with GitHub, LinkedIn, Email, Phone
- 🔗 Clickable hyperlinks with `hyperref`
- 🎯 New sections: Profile, Technical Experience, Technologies
- 📄 One-page compact layout by default
- 📚 Indian academic formatting (e.g., board percentages, coursework lists)

---

## 📁 Class Variants

| Class File        | Spacing Style              | Use Case Example                            |
|-------------------|----------------------------|----------------------------------------------|
| `mcdowellcv_2.cls` | Tighter spacing            | Fewer items but more readable spacing  |
| `mcdowellcv_3.cls` | Balanced (default) spacing | General-purpose student CVs                 |
| `mcdowellcv_4.cls` | Looser spacing             | Fitting 2–3 experiences, projects on 1 page     |

---

## 🧾 Visual Previews

Below are sample renderings of each class variant to help you pick the best fit:

| `mcdowellcv_2.cls` (Tight Spacing) | `mcdowellcv_3.cls` (Balanced Spacing) | `mcdowellcv_4.cls` (Loose Spacing) |
|------------------------------------|----------------------------------------|------------------------------------|
| ![Tight spacing](samples/mcdowellcv_2.png) | ![Balanced spacing](samples/mcdowellcv_3.png) | ![Loose spacing](samples/mcdowellcv_4.png) |



To use a version, set in your `.tex` file:

```latex
\documentclass[]{mcdowellcv_3} % or _2 / _4
