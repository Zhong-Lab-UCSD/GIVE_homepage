__*GIVE*__  is an open source programming library that allows anyone without much programming experience to build custom genome browser websites or apps. With a few lines of codes, one can set up GIVE service on a local machine, manage custom data and build an interactive genome browser. Besides, we established **GIVE-Hub**, a data center providing GIVE service and hosting public/customer data sets, such as ENCODE data. It takes only a few minutes to build a genome browser website using GIVE-Hub.

This portable library encapsulates novel data communication and data visualization technologies, including new data structures and new memory management methods that enable efficient data transfer between the data-hosting website and internet browsers. 
GIVE is the acronym of **G**enomic **I**nteraction **V**isualization **E**ngine, although GIVE's utilities have outgrown its original name.

- [**GIVE Tutorial**](https://github.com/Zhong-Lab-UCSD/Genomic-Interactive-Visualization-Engine/tree/master/tutorials): From zero to expert! Step-by-step tutorials with comprehensive examples show you how to elegently customize a genome browser with GIVE
- [**GIVE Manual**](https://github.com/Zhong-Lab-UCSD/Genomic-Interactive-Visualization-Engine/blob/master/manuals/): Technical details for users or developers who want to learn more about GIVE. 
- [**GIVE-Hub**](https://www.givengine.org/give-hub.html): The UCSD data center providing GIVE service and hosting hundreds of public/customer data source. 
                                                                          

## [A 2-minute tutorial](https://jsfiddle.net/frankyan/mcdng033/)

Just copy paste the following HTML codes to [jsfiddle](https://jsfiddle.net/), an online HTML testing website for testing of your own HTML codes. 1) Go to  [jsfiddle](https://jsfiddle.net), 2) copy paste the following lines to the HTML panel (top left), 3) hit "run" button.
Congratulations! You have built your first genome browser webpage using GIVE-Hub data source in less than 1 minute. 
```html
<!-- header source -->
<script src="https://www.givengine.org/bower_components/webcomponentsjs/webcomponents-lite.min.js"></script> 
<link rel="import" href="https://www.givengine.org/components/chart-controller/chart-controller.html">

<!-- embed the browser in the web page -->
<chart-controller 
  title-text="A 2-minute starter of building a genome browser with GIVE" 
  ref="hg19" 
  num-of-subs="2" 
  coordinates='["chr18:19140000-19450000", "chr18:19140000-19450000"]'
  group-id-list='["genes", "CHi-C_promoter"]'
></chart-controller>
```
So you have enough time to learn some essential tips for customizing your genome browser. Please read the [GIVE Tutorial 0: Building a Customized Genome Browser within 2 minutes](https://github.com/Zhong-Lab-UCSD/Genomic-Interactive-Visualization-Engine/blob/master/tutorials/0-shortexample.md). The following GIF animation shows the whole process of the 2 minute tutorial. It's so easy.

![2 minute show](figures/2-minutes-show.gif)

How to use your own data instead of GIVE-Hub data source? It's easy! Just learn more from [GIVE tutorials](https://github.com/Zhong-Lab-UCSD/Genomic-Interactive-Visualization-Engine/tree/master/tutorials)! You can set up your own GIVE service and build a powerful genome browser with you own data in less than 2 hours!

****************

## Examples of custom genome browsers built with GIVE using GIVE-Hub data source

<table>
  <tr style="padding-bottom:10px;">
    <td width="60%">
      <a href="https://singlecell.genemo.org">Single-cell transcriptome website</a>
    </td>
    <td width="40%">
      <a href="https://singlecell.genemo.org"><img src="figures/give_singlecell.png" width="400px"></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="60%">
      <a href="https://encode.genemo.org">A web browser for human ENCODE datasets</a>
    </td>
    <td width="40%">
      <a href="https://encode.genemo.org"><img src="figures/give_encode.png" width="400px"></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="60%">
      <a href="https://margi.givengine.org">A website for genome-wide RNA-DNA interactions</a>
    </td>
    <td width="40%">
      <a href="https://margi.givengine.org"><img src="figures/give_RNAinteraction.jpg" width="400px"></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="60%">
      <a href="https://chic.givengine.org">A website for displaying genome interaction (Capture Hi-C) data</a>
    </td>
    <td width="40%">
      <a href="https://chic.givengine.org"><img src="figures/give_hic1.png" width="400px"></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="60%">
      <a href="https://chiapet.givengine.org">A website for displaying genome interaction (ChIA-PET) data</a>
    </td>
    <td width="40%">
      <a href="https://chiapet.givengine.org"><img src="figures/give_chiapet.png" width="400px"></a>
    </td>
  </tr>
</table>
----------------

Citation: Xiaoyi Cao, Zhangming Yan, Qiuyang Wu, Alvin Zheng, Sheng Zhong, Building a genome browser with GIVE,  bioRxiv, 2017, [https://doi.org/10.1101/177832](https://doi.org/10.1101/177832).

----------------

© COPYRIGHT 2017 GIVE Authors. Code Licensed under the Apache License 2.0. Documentation licensed under CC BY 3.0. 
