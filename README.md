# Irrigation Infrastructure and Conflict Mitigation in Indonesia

![](images/image.png)

### Purpose

The pourpose of this repository was to replicate and interpret two core empirical models from (Gatti et. al 2020), titled *"Can Irrigation Infrastructure Mitigate the Effect of Rainfall Shocks on Conflict? Evidence from Indonesia"* .

The paper asks a deceptively simple question: **when the rains fail and crops suffer, does having irrigation infrastructure keep a community calmer?** Using district-level panel data from Indonesia (1998–2014), the authors find that low growing-season rainfall increases civil conflict, but that this effect is meaningfully dampened in districts with greater irrigation capacity. The mechanism they propose is agricultural: irrigation buffers farm income during droughts, which in turn reduces economically-motivated violence.

### Contents

This repository contains:

```         
.
├── assignment_4_final.qmd
├── blog_post_final.qmd  # Rendering this produces final analysis
├── data # This folder will need to be created, see data access section.
│   ├── AJAE MS#19355-Data and Codes-Gatti
│   ├── do_file.do
│   ├── irrigation_data.csv
│   └── ols_spatial_HAC.ado
├── eds241-final-project.Rproj
├── images
│   └── image.png
├── .gitignore
└── README.md
```

### Contributors

-   Austin Martinez
-   Aakriti Poudel
-   Henry Oliver

### Data Access

ajae12092-sup-0001-supinfo/AJAE MS#19355-Data and Codes-Gatti/data.dta

The for this project was sourced from the Supporting Information section of ([Gatti et. al, 2020](https://onlinelibrary.wiley.com/doi/10.1002/ajae.12092)). Clicking the following link will download a zip file containing this studies data.

[Data link](https://onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1002%2Fajae.12092&file=ajae12092-sup-0001-supinfo.zip)

Zip file has the following file structure:

-   ajae12092-sup-0001-supinfo/AJAE MS#19355-Data and Codes-Gatti/data.dta

-   Create a folder within this project titled data, populate with `AJAE MS#19355-Data and Codes-Gatti` folder.

-   Use second code chunk of `blog_post_final.qmd` to convert the DTA to a CSV

### References

-   Gatti, N., Maertens, M., & Vandercasteelen, J. (2020). Can irrigation infrastructure mitigate the effect of rainfall shocks on conflict? American Journal of Agricultural Economics, 102(5), 1281–1305. <https://doi.org/10.1111/ajae.12124>
