statistics 157, earthquake data project
=====

Goals
-----
  - Class Goal
    - To produce an earthquake alarm error optimization model that more accurately predicts BG Luen's model through comparisons between the accuracy of three models: the Epidemic-Type Aftershock Sequence (ETAS), Poisson, and Magnitude-Dependent Automatic Alarm (MDA).
  - Horizontal Goals
    - _Curator_
      - To scrape, clean, and present a data frame with information from the USGS Earthquake monitoring system updating in realtime.
    - _Analyzer_
      - To compare multiple methods of understanding earthquake data utilizing the Curator's data frame in the form of a `.ppx` file.
      - To understand ETAS: Through R, analyze the Curator's data with three (3) downloadable packages: `ETAS`, `SAPP`, & `PtProcess`.
      - To understand MDA: Utilize R's functions in explaining the model alarm system.
    - _Visualizer_
      - Using the Analyzers' outputs, visualize the multiple methods and understand through comparison if there is a more accurate indicator of earthquake alarms.
      - Understand the models more accurately to develop a clear mathematical understanding of the models, parameters, and produced outputs.  
  - **S.M.A.R.T. Goals**
    - [**S**] Specific: To Produce a Final, More Accurate Model of Earthquake Alarm Errors Using B.G. Luen's Ph.D [Dissertation](https://github.com/j-zhang/analyzers/blob/master/resources/luen_paper.pdf) & [Presentation](http://www.stat.berkeley.edu/%7Ebradluen/slides.pdf) as a Comparison & Starting Point
    - [**M**] Measurable: With 3 Curator Groups, 3 Analyzer Groups, & 4 Visualizer Groups, We Want to Understand all Data & Models In Order to Compare Various Ways of Examinng Earthquake Alarm Error Data
    - [**A**] Attainable: Break Down Project into Segements That Can Be Achieved In One Week Increments
    - [**R**] Relevant: Stay on Track and Focused on End Result
    - [**T**] Time-Bound: Weekly Updates on Tuesday Mornings Of Each Group's Progress By Presenters & Weekly Meetings with _ALL_ Presenters to Understand Progress
    - **S.M.A.R.T._E_._R_. Goals**
      - [**E**] Evaluate: Curators Will Round Out the Process of Keeping **ALL** Groups Accountable with Meeting Expected Results and Reproducibility Requirements
      - [**R**] Re-Evaluate: Presenters Will Work Together to Keep Eachother On The Same Page and On Task With Weekly Meetings & the Final Compilation of the Project Entirity

Horizontals & Divided Sub-Groups
-----
**Note**: Presenters will be the group contacts between sub-groups.  These contacts are **bolded** within their respective groups.
- Curators ( [Resository](https://github.com/stat157/data-curators) )
  - **A**, Cache Money ( [S.M.A.R.T Goals](https://github.com/wliang88/Earthquake-Curators/blob/master/README.md) )
    - Arif Ali                ( [arifyali](https://github.com/arifyali) )
    - David BARRERA           ( [jest4pun](https://github.com/jest4pun) )
    - Kimberly LE             ( [kimberlyle](https://github.com/kimberlyle) )
    - **Wen LIANG**               ( [wliang88](https://github.com/wliang88) )
    - Xiaorui "Sherry" XIA    ( [xsherryxia](https://github.com/xsherryxia) )
  - **B** ( [S.M.A.R.T Goals](https://github.com/stat157/presenters/issues/10) )
    - Alisha AGRAWAL          ( [alisha791](https://github.com/alisha791) )
    - Theresa ANDRASFAY       ( [tandrasfay](https://github.com/tandrasfay) )
    - **Lorraine HSIAO**          ( [lorrainehsiao](https://github.com/lorrainehsiao) )
    - Jie ZHANG               ( [jzhang980](https://github.com/jzhang980) )
    - Qi ZHANG                ( [qi-zhang](https://github.com/qi-zhang) )
  - **C**, Smile ( [S.M.A.R.T Goals](https://github.com/stat157/background/issues/25) )
    - Timothy HOANG           ( [timothyhoang](https://github.com/timothyhoang) )
    - Reena SHAH              ( [reenashah](https://github.com/reenashah) )
    - Yuqi "Tristan" TAO                ( [tristantao](https://github.com/tristantao) )
    - **David WANG**              ( [davidwang001](https://github.com/davidwang001) )
- _Readjustment of Curators, Post-Curation of Data Completion_
  - **Writing Team**
    - Xiaorui "Sherry" XIA (Writing Team)    ( [xsherryxia](https://github.com/xsherryxia) )
    - Theresa ANDRASFAY (Writing Team) ( [tandrasfay](https://github.com/tandrasfay) )
    - Jie ZHANG (Writing Team)( [jzhang980](https://github.com/jzhang980) )
  - **Reassigned Curator Groups**
    - Analyzers 1: _Kimberly LE_ ( [kimberlyle](https://github.com/kimberlyle) )
    - Analyzers 2: _Arif ALI_ ( [arifyali](https://github.com/arifyali) )
    - Analyzers 3: _Qi ZHANG_  ( [qi-zhang](https://github.com/qi-zhang) )
    - Visualizers #: _Timothy HOANG_ ( [timothyhoang](https://github.com/timothyhoang) ) &  _Reena SHAH_ ( [reenashah](https://github.com/reenashah) )
    - Visualizers $: _Yuqi "Tristan" TAO_ ( [tristantao](https://github.com/tristantao) )
    - Visualizers Q: _David BARRERA_ ( [jest4pun](https://github.com/jest4pun) )
    - Visualizers ❤: _Alisha AGRAWAL_ ( [alisha791](https://github.com/alisha791) )

- Analyzers ( [Repository](https://github.com/stat157/analyzers) )
  - **1**  ( [S.M.A.R.T Goals](https://github.com/stat157/background/issues/13) )
    - Teresa TENFELDER        ( [teresita](https://github.com/teresita) )
    - Khoa TRAN               ( [kqdtran](https://github.com/kqdtran) )
    - **Roland SHEN**              ( [rolandshen](https://github.com/rolandshen) )
    - Jody ZHANG              ( [j-zhang](https://github.com/j-zhang) )
  - **2** ( [S.M.A.R.T Goals](https://github.com/stat157/background/issues/24) )
    - **Laura CUNNINGHAM**        ( [lauraccunningham](https://github.com/lauraccunningham) )
    - Disi KOA                ( [gnolnait](https://github.com/gnolnait) )
    - John RISKO              ( [johnrisko](https://github.com/johnrisko) )
    - Tay SHIN                ( [taywon](https://github.com/taywon) )
  - **3** ( [S.M.A.R.T Goals](https://github.com/stat157/background/issues/23) )
    - Bonghyun KIM            ( [bonghyun5](https://github.com/bonghyun5) )
    - Yee Tung "Alice" MAN    ( [amx01](https://github.com/amx01) )
    - **Alyssa PARKER**           ( [aparker92](https://github.com/aparker92) )

- Visualizers ( [Repository](https://github.com/stat157/visualizers) )
  - **#**  ( [S.M.A.R.T Goals]() )
    - **David LAU**               ( [davidopluslau](https://github.com/davidopluslau) )
    - Ashley SIA              ( [ashleysia](https://github.com/ashleysia) )
    - Raymond MA              ( [raymondma1](https://github.com/raymondma1) )
    - Yoojin JANG             ( [all4ujin](https://github.com/all4ujin) )
    - Vincent CANLAS          ( [vcanlas](https://github.com/vcanlas) )
  - **$** ( [S.M.A.R.T Goals](https://github.com/joyyqchen/EarthquakeProject.Team-Chen.Kirschner.Liou.Tsai) )
    - **Brian LIOU**              ( [brianliou](https://github.com/brianliou) )
    - Tinghui "Eric" TSAI     ( [wxadqcze](https://github.com/wxadqcze) )
    - Joy CHEN                ( [joyyqchen](https://github.com/joyyqchen) )
    - Sam KIRSCHNER           ( [drmeow](https://github.com/drmeow) )
  - **Q, Quakers** ( [S.M.A.R.T Goals](https://github.com/SunnySunnia/TheQuakers/blob/master/README.md) )
    - **Carl SHEN**               ( [carlshan](https://github.com/carlshan) )
    - He MA                   ( [sunnymh](https://github.com/sunnymh) )
    - Siyang "Sunny" ZENG     ( [sunnysunnia](https://github.com/sunnysunnia) )
    - Alex CHAO               ( [alexchao56](https://github.com/alexchao56) )
  - **❤** ( [S.M.A.R.T Goals](https://github.com/stat157/background/issues/22) )
    - **Hong SHON**               ( [tzenarr](https://github.com/tzenarr) )
    - Hyung Kyu CHANG         ( [hkchang89](https://github.com/hkchang89) )
    - Sunghoon CHOI           ( [shchoi](https://github.com/schoi) )
    - Christina HO            ( [chocoho](https://github.com/chocoho) )
    - Jinsoo LEE              ( [annyeongjs](https://github.com/annyeongjs) )

- **UNASSIGNED INDIVIDUALS**: Someone please contact them and get them in the loop/working within a group.  Please make a new issues with the group they will be working in.
    - Kuanwei TSENG           ( [kt0009](https://github.com/kt0009) )

Working Diagram
-----
- Step 1
  - Curators:
      - C --> B --> A --> Curator Output
        - C: Scrape USGS Data & Prepare Simple Data Frame
        - B: Cleaning Data and Formating as a `.csv` File
        - A: Translating `.csv` File into a Necessary `.ppx` Format to be Run Through the `ETAS` Package in R, as well as Cleaning Data to exclude Not Applicable (N/A) Values
      - Curator Output Includes Two Files: 
        - `.csv` File --> _CuratorOutput1_
        - `.ppx` File --> _CuratorOutput2_
- Step 2
  - Analyzers:
      - Curator Output --> Analyzer Sub-Groups 1, 2, 3
        - 1: Analyzing Curator Output through the MDA Model, Using R --> Outputing Information as _AnalyzerOutput1_
        - 2 & 3: Combined objectives Separated between the Two Groups ( A Detailed Needs Assement Can Be Found [Here](https://github.com/stat157/background/issues/26) )
          - 2: Analyzing Curator Output through the ETAS Model, Using R Package `SAPP` and `PtProcess` --> Outputing Information as _AnalyzerOutput2_
          - 3: Analyzing Curator Output through the ETAS Model, Using R Package `SAPP` and `PtProcess` --> Outputing Information as _AnalyzerOutput3_
      - Analyzer Outputs: _AnalyzerOutput1_, _AnalyzerOutput2_, _AnalyzerOutput3_
- Step 3
  - Visualizers
      - Analyzer Outputs (_AnalyzerOutput1_, _AnalyzerOutput2_, _AnalyzerOutput3_) --> Pushed to Specific Visualizer Groups
        - Paths of Analyzer Outputs to Visualizer Groups:
          - _CuratorOutput1_ or _CuratorOutput2_ --> #
          - _AnalyzerOutput1_ --> $ 
          - _AnalyzerOutput2_ --> Q
          - _AnalyzerOutput3_ --> ❤

What the Visualizers Will Be Examining & Expected Results
-----
  - #: 
    - Look at the _Curator Output_ as Raw Data & Create a Plot
      - Plot Needs to Include Earthquakes on a World Map with Points Dependent Upon the Individual Earthquake's Magnitude (Size of Point), Depth (Color of Point: Red (Deeper) to Green (Shallower), Adjust Gradient to Clarify the Layering of Earthquake in Close Proximity to One Another)
    - Put Together A Comprehensive Understanding of the Magnitude-Dependent Alarm (MDA) Model
  - $: 
    - Examine & Create a Visual Representation of _AnalyzerOutput1_ --> Create _VisualOutput1_
    - Compare _VisualOutput1_ with _VisualOutput2_
  - Q: 
    - Examine & Create a Visual Representation of _AnalyzerOutput2_ --> Create _VisualOutput2_
    - Put Together A Comprehensive Understanding of the Epidemic-Type Aftershock Sequence (ETAS) Model, Preliminary Understand `ETAS` R Package
  - ❤: 
    - Examine & Create a Visual Representation of _AnalyzerOutput3_ --> Create _VisualOutput3_
    - Compare _VisualOutput2_ with _VisualOutput3_

**Note**: To Keep Ourselves in Check, We will be Reappropriating Those involved with the Curator Process with the Checking of Processes & Individuals to Hold Individuals Accountable for Reproducibilty Errors
