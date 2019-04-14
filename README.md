# OverlayChecker

This is a repository for dataset of OverlayChecker.<br/>
For some limitations, we partially disclose our dataset in [link](https://share.weiyun.com/5VjkGAI).<br/>

In file in the link above, there are 64 columns.<br/>
The meaning of each column is as follows:<br/>

1     : Index of each row<br/>
2     : Task_ID of each detected overlay<br/>
3     : Label of the app which the detected overlay is in, 0 represents benign, 1 represents malicious<br/>
4-5   : X and Y coordinates of the upper left corner of the detected overlay<br/>
6-7   : Width and Height of the detected overlay<br/>
8     : Total number of detected overlays in one task<br/>
9-39  : Flags of the detected overlay<br/>
40-44 : Gravity of the detected overlay<br/>
45-47 : Format of the detected overlay<br/>
48-57 : Type of the detected overlay<br/>
58    : Alpha value of the detected overlay<br/>
59    : Whether the detected overlay is opaque, 0 represents false, 1 represents true<br/>
60    : Whether the detected overlay has a background, 0 represents false, 1 represents true<br/>
61    : Whether the app which the detected overlay is in requested for root, 0 represents false, 1 represents true<br/>
62    : Whether the app which the detected overlay is in requested for screenshot, 0 represents false, 1 represents true<br/>
63    : Whether the app which the detected overlay is in has the permission of BIND_ACCESSIBILITY_SERVICE, 0 represents false, 1 represents true<br/>
64    : Whether the app which the detected overlay is in has the permission of PACKAGE_USAGE_STATS, 0 represents false, 1 represents true<br/>


Our paper has been conditionally accepted for [MobiSys 2019](https://www.sigmobile.org/mobisys/2019/).<br/>
Please cite this study when using the data.<br/>

##### Contact:
<yanyx15@tsinghua.org.cn><br/>
<lizhenhua1983@tsinghua.edu.cn>
