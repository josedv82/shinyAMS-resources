# Building Shiny Athlete Management Tools
### A compilation of resources for Sport Scientists using Shiny to build athlete management tools.
##### Jose Fernandez
---

### **Intro**

Professional sports organizations have exponentially increased the adoption of new technologies and access to broader and larger amounts of information in recent years. Furthermore, medical and performance departments have also grown in size with more staff members and a wider variety of backgrounds (ATCs, S&C, Rehab Coaches, Sport Scientist, Nutritionits, Sport Psychologists, etc.). As a result, the demand for platforms that leverage aggregation, interpretation, reporting and sharing of this information at different levels within and across departments is becoming more relevant.

Sport Scientists often work at the intersection of coaching and analysis with direct responsibilities for disseminating this information in ways that are meaningful and user friendly. The more refined this process is, the higher the opportunity for all relevant members of the staff to integrate this information within their decision making strategy. Generally speaking (and acknowledging the fact that this is rapidly evolving), sport scientists have traditionally lacked programming skills outside common platforms such as Microsoft Excel, increasing the need to rely on commercial products, also known as Athlete Management Systems (AMS), to aid with data reporting and sharing.

### About this document

Over the last decade I've been exposed in different ways to some of the most common AMS platforms available to sport medicine and performance teams. I have also been involved in designing, building and deploying athlete data management solutions using a variety of business intelligence tools. In recent years, I started to rely more on [Shiny](https://shiny.rstudio.com/) than other options as my framework of choice to build interactive web applications, some of which, ended up fully replacing commercial software, some others were simply developed to cover a specific need that other products were not able to cover at that exact time.

Some degree of familiarity with the [R language](https://www.r-project.org/about.html) and Shiny programming is needed to better understand the resources shown on this document. If this is not the case, I recommend checking out some of the many great publicly available [materials](https://mastering-shiny.org/) to learn the basics of Shiny. My goal is to highlight and discuss various elements I tend to include or have the potential to improve user-app interaction, engagement and overall experience. As you can see, most of the focus will be on the [User Interface (UI)](https://en.wikipedia.org/wiki/User_interface) side of things.

When I first started building Shiny apps I found myself investing large amounts of time researching how to do that specific thing (element, functionality, desired look, etc...) I wanted to implement. My hope is that this document can help others that are going through the same by compiling a list of useful resources and showing minimal examples on how they can be used (examples will be added over time).

<br>

I hope you find this document useful. If you feel I can be of any help or if you would like to discuss further any of this content please feel free to reach out. You can contact me via [email](mailto:jose.fernandezdv@gmail.com) or through my [twitter](https://twitter.com/jfernandez__) account. Likewise, if you have any feedback to improve this document (be it via missing resources or code examples) please do not hesitate to let me know.

Best,  
Jose Fernandez

```
Big thanks to those investing their time and knowledge to build these resources for others to use
```

<hr>


### 1. **Dashboarding**
##### 1.1 Basic Shiny
- [Learning Materials](https://shiny.rstudio.com/tutorial/)

##### 1.2 Shinydashboard
- [Expands dashboarding functionality](https://rstudio.github.io/shinydashboard/index.html)

##### 1.3 Html Templates
- [Rinterface](https://rinterface.com/)  
- [Shiny Semantic](https://github.com/Appsilon/shiny.semantic) 

##### 1.4 Mobile Devices
- [shinyMobile](https://rinterface.github.io/shinyMobile/index.html)
- [MiniUI](https://github.com/rstudio/miniUI)

### 2. **Theming**
- [ShinyThemes](https://rstudio.github.io/shinythemes/) 
- [Dashboardthemes](https://github.com/nik01010/dashboardthemes)
- [Fresh](https://github.com/dreamRs/fresh)  
- [shinyMaterial](https://ericrayanderson.github.io/shinymaterial/) 


### 3. **Showing Data**  
##### 3.1 Static Plots  
- [Base R](https://rstudio-pubs-static.s3.amazonaws.com/7953_4e3efd5b9415444ca065b1167862c349.html)  
- [Ggplot2](https://ggplot2.tidyverse.org/)

##### 3.2 Interactive Plots
- [Plotly](https://plotly.com/r/)  
- [Echarts4R](https://echarts4r.john-coene.com/)
- [sparkline](https://github.com/htmlwidgets/sparkline)
- [dataui](https://timelyportfolio.github.io/dataui/index.html)

##### 3.3 Mobile Charts
- [mobileCharts](https://shiny.john-coene.com/mobileCharts/)

##### 3.4 Tables
- [Gt](https://gt.rstudio.com/) 
- [DT](https://rstudio.github.io/DT/) 
- [Formattable](http://renkun-ken.github.io/formattable/)    
- [Flextable](https://davidgohel.github.io/flextable/)  
- [Reacttable](https://glin.github.io/reactable/) 
- [Graphical Tables](https://pdfs.semanticscholar.org/76a0/c9984d656592f2979569e895333de21464bb.pdf?_ga=2.39740005.714811824.1593711014-2057169377.1593711014)  

##### 3.5 Editable Tables
- via [DT](https://blog.rstudio.com/2018/03/29/dt-0-4/) 
- [DTedit](https://github.com/jbryer/DTedit)
- [RhandsonTable](https://cran.r-project.org/web/packages/rhandsontable/vignettes/intro_rhandsontable.html)

##### 3.6 Pivot Tables
- [pivottabler](http://www.pivottabler.org.uk/articles/)
- [rpivotTable](https://github.com/smartinsightsfromdata/rpivotTable)
- [pivta](https://github.com/feddelegrand7/pivta)

### 4. **Notifications / Alerts / User Feedback**
##### 4.1 Basic Shiny
- [Basic Notifications](https://shiny.rstudio.com/articles/notifications.html) 
- [Modals](https://shiny.rstudio.com/articles/modal-dialogs.html)

##### 4.2 Via package
- [ShinyAlert](https://github.com/daattali/shinyalert) 
- [Toastr](https://github.com/MangoTheCat/shinytoastr) 
- [sweetAlert](http://shinyapps.dreamrs.fr/shinyWidgets/) (via shinyWidgets)  
- [shinyFeedback](https://github.com/merlinoa/shinyFeedback) 
- [shinyPop](https://github.com/dreamRs/shinypop)

### 5. **Forms**
- Form Code example (to do)  
- [shinyForms](https://github.com/daattali/shinyforms)
- [FAQ Section](https://github.com/jienagu/faq)

### 6. **User Inputs**
- [Basic inputs](https://shiny.rstudio.com/tutorial/written-tutorial/lesson3/) 
- [shinyWidgets](http://shinyapps.dreamrs.fr/shinyWidgets/)  
- [shinyBody](https://github.com/MayaGans/shinyBody) 
- [DT Editable Input](https://github.com/jienagu/DT_editable_as_shiny_input)
- [shinyRatingInput](https://github.com/stefanwilhelm/ShinyRatingInput) 
- [shinyReactWidgets](https://github.com/pvictor/shinyReactWidgets)

### 7. **Loaders**
- [shinyCSSLoaders](https://github.com/daattali/shinycssloaders) 
- [shinyCustomLoader](https://emitanaka.org/shinycustomloader/)
- [shinyBusy](https://dreamrs.github.io/shinybusy/)
- [Waiter](https://waiter.john-coene.com/#/)

### 8. **Icons**
- [Fontawesome](https://fontawesome.com/)
- [Glyphicon](https://getbootstrap.com/docs/3.3/components/) 
- [Use your own image](https://gist.github.com/hrbrmstr/605e62c5bf6deadf304d80cf4b1f0239)  (example)

### 9. **Calendars**
- [tuicalendr](https://github.com/dreamRs/tuicalendr)

### 10. **Error Messages**
- [Basic Sanitizing](https://shiny.rstudio.com/articles/sanitize-errors.html)
- [via Validation](https://shiny.rstudio.com/articles/validation.html) 
- [via CSS (supress errors)](https://stackoverflow.com/questions/24652658/suppress-warning-message-in-r-console-of-shiny)
- [sever (via cleave)](https://sever.john-coene.com/cleave/)

### 11. **Expanded Functionalities**
- [ShinyJS](https://deanattali.com/shinyjs/)
- [pushBar](https://github.com/JohnCoene/pushbar)
- [Effects](https://github.com/RinteRface/shinyEffects)
- [shinyjqui](https://github.com/Yang-Tang/shinyjqui)

### 12. **File Access**
- [shinyFiles](https://github.com/thomasp85/shinyFiles)

### 13. **Big AMS**
- [Modules](https://shiny.rstudio.com/articles/modules.html)

### 14. **User Authentication**
- [firebase](https://github.com/JohnCoene/firebase)
- [shinyauthr](https://github.com/PaulC91/shinyauthr)
- [shinymanager](https://datastorm-open.github.io/shinymanager/)
- [polished](https://polished.tech/)

### 15. **App Reloading**
- [sever](https://sever.john-coene.com/)
- [shinyDisconnect](https://github.com/daattali/shinydisconnect)

### 16. **App Tutorials / Tours**
- [Cicerone](https://github.com/JohnCoene/cicerone)
- [introJS](https://github.com/carlganz/rintrojs)

### 17. **Emailing**
- [Native tutorial](https://www.r-bloggers.com/download-and-email-reports-in-r-shiny-app/)
- [mailtoR](https://github.com/feddelegrand7/mailtoR)

### 18. **Exporting Options**
- [Download any type of report](https://www.r-bloggers.com/download-and-email-reports-in-r-shiny-app/)
- [another example](https://shiny.rstudio.com/articles/generating-reports.html)
- [Exporting user notes](https://github.com/jienagu/noteMD)

### 19. **Images**

- [shinyGallery](https://github.com/stefanieschneider/shinygallery)

## Final notes:

This document is an extension of a previous [Twitter thread](https://twitter.com/jfernandez__/status/1197909220890480640)

<img width="350" src="https://www.dropbox.com/s/7tal1q153xi3jo7/shinytweet.png?raw=1">

