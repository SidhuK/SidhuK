<h4 align="Center"> 👋 </h2>

```R

SidhuK <- function(Karat_Sidhu) {
    username <- "SidhuK"
    name <- "Karat Sidhu"
    website <- "https://karat.science/"
    twitter <- "https://x.com/@karat_sidhu"
    linkedin <- "https://linkedin.com/in/karatsidhu"
    code <- c(
        main_coding_languages = c("R", "Python"),
        tools = c("TidyVerse", "Quarto", "RMarkdown", "Git",
                "GitHub", "Pandas", "Jupyter","Numpy", "Matplotlib", "Seaborn")
    )
    scientific_skills <- c(
        research = c("Metabolomics", "Proteomics","Mass Spectrometer",
                    "LC/MS/MS", "Cell_Biology", "Small Molecule Analysis"),
        equipment = c("Q-TOFs", "UPLC", "HPLC", "QqQ"),
        academic = c("Biotechnology", "Analytical Chemistry", "Biochemistry")
    )
    personal_interests <- c("Reading", "Painting", "Running", "Skiing")

    Karat_Sidhu <- list(username, name, website,
                        twitter, linkedin, data.frame(code),
                        data.frame(scientific_skills), data.frame(personal_interests))

    return(Karat_Sidhu)
}

SidhuK(Karat_Sidhu)


```

<h4 align="center">✌️</h4>
