# 📄 Modeling and Analyzing Social Networks of Games

This repository presents a collection of codes and datasets from the research paper "Modeling and Analyzing Social Networks of Games". To identify attractive components of platform games and player preferences, we analyzed data from the famous Super Mario Maker game created by Nintendo Inc. in Kyoto, Japan.   

**Paper**: _under submission review_.

> **Abstract**: Digital games are dynamic environments where the players interact with the games and, commonly, also with other players. The interactions generate many types of relationships, such as to be friends or to share games with other players, and to buy, play or like the games. These relationships can be seen as a social network; in this context, a Social Network of Games (SNG). During gameplay, the player produces a vast amount of data continuously, including data that represents his/her experiences, preferences, and even behavioral patterns. These data can be used to understand the players’ preferences, which is known in the literature as Player Modeling, and also to improve the attractiveness of new games. However, both tasks require analyzing a vast amount of data that cannot be done manually; it must be performed by algorithms of a research area known as Knowledge Discovery in Databases (KDD). It is possible to employ KDD techniques in the data of an SNG to model the players, as well as to identify intrinsic features of the games. In our work, we explore a real SNG using a novel KDD technique aimed at identifying common features among popular games, which may represent why the games are popular. To this end, it is necessary to analyze games developed by non-influencer makers, because influencers may receive biased attention that is not necessarily motivated by the quality of their games. Therefore, we first focus on detecting the game influencers to filter their games out; empirical experiments show that a novel approach we developed detects influencers with high accuracy in an automatic manner, even when using data from distinct nationalities for training and testing. Then, we perform a detailed analysis of the features of the games, searching for combinations of objects that occur in the popular games developed by non-influencer makers, where each object can be either a game item or a non-player character, so to support game designers in the elaboration process of new games. This case study introduces a new pattern of design for Platform Games. Additionally, we present an extensive analysis of object combinations that commonly occur in popular games. All experiments were performed on real-world players and games from the worldwide well-known platform of video games Super Mario Maker (Nintendo, Kyoto, Japan).

---
## Repository Structure

We have sorted the resources into three separate folders.
- 📝 [analysis/](analysis/) - Codes and analysis performed.
- 🎲 [data/](data/) - Datasets elaborated from this research.
- 🔧 [tool/](tool/) - Tools to support the creation and extraction of datasets.

To help research paper readers, these are the link of sections and resources in the article.

- Section 3. Crawling a Social Network of Games
    - 📝 `analysis/smmnet/` - Data analysis and visualization. 
    - 🎲 `data/` - SMMnet is available on [kaggle](https://www.kaggle.com/datasets/leomauro/smmnet).
    - 🔧 `tool/smm-maker-profile/` - Tool that collects players' data.
    - 🔧 `tool/smm-course-search/` - Tool that searches for levels developed.
- Section 4. Detecting Game Influencers
    - 📝 `analysis/detecting-influencers/` - Feature extraction codes and visualization.
    - 🎲 `data/` - SMMnet and intermediate data are in the code folder.
- Section 5. Characterizing Popular Games
    - 📝 `analysis/characterizing-popular-games/` - Analysis on popular games.
    - 🎲 `data/characterizing-popular-games/` - Features and aggregated features extracted.
    - 🔧 `tool/smm-course-viewer/` - Tool that extract features from course files.

---
## Download

To download all files and subfolders use the following Git command:

```shell
$ git clone --recurse-submodules https://github.com/leomaurodesenv/modeling-analyzing-social-networks-of-games.git
```

---
## Citation

The citation will be updated when accepted, _paper is under submission review_.

```tex
@misc{moraes:2023:modeling-social-network-of-games,
    author={Leonardo Mauro Pereira Moraes and Felippe P. Ferreira and Robson Leonardo Ferreira Cordeiro},
    title={Modeling and Analyzing Social Networks of Games},
    year={2023},
    url={https://github.com/leomaurodesenv/modeling-analyzing-social-networks-of-games},
}
```

---
## Also look ~

-   License: _not defined_
-   Citation: _not defined_
-   Created by [leomaurodesenv](https://github.com/leomaurodesenv/)
