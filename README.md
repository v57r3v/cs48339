java c
OM 252, Winter 2025 
HW 3 
Assigned: Jan 23, 2025, 9 AM 
Due: Jan 29, 2025, 11:59 PM
Instructions:   Each assignment will   include a   PDF file   (like this one)   with   the   assignment   questions   and   an   Excel file with an Answers sheet and   any   data   or   models   we   provide.   You   must   download   both   the   PDF and   Excel files. You   must enter your answers   in the Answers   sheet   of the   same   Excel   file   you downloaded, then save and   upload the   Excel file. You   must   upload the   same   Excel file   you   downloaded.   Further   instructions are   provided   in the Online Assignment Tools Guide   (see Assignments on   Canvas). 
Put your answers   in the appropriate cells   (salmon-colored   cells)   in the Answers sheet.   Use paste special … values for all   numerical answers. The other   cells   in the   Answers   sheet   are   locked,   which   means   you won’t   be able to enter values   into those cells.   Do   not   change   the   format   of   cells   in the   Answers   sheet.   Save your file with the appropriate   name and   in the   proper format   (“HW#_ID.xlsx”). 
Marking will   be   based on the answers   in the Answers worksheet   of the   file   you   upload.   We   will   only   look   at the   rest of the file   if there   is an appeal   (and   even   then,   the   answers   in   the   Answers   sheet   take precedence.)   If you wish to appeal a   mark, the   uploaded file   must   include your   supporting   work   for   each   question.   It   is a good   idea to   make one worksheet for   each   question. 
Total points: 35, of which   2   points are for following   the   submission   instructions   provided   above.
Forecasting Number of Building Permits Issued in Edmonton 
In this assignment,   we   use a different   data   set   related to   the   number   of   building   permits   issued   by   the City of   Edmonton. Our   interest   is   in forecasting the   number of   permits   issued   in the future.   The “Data” sheet shows the total   number of   permits   issued for every   month from   January   2015   to   December   2024.
You will   use this data for   all   of your work   on   this   assignment.   Here   is   a   plot   of   the   monthly   data:
Let   us   begin   by   plotting the data.

From   Figure   1, We observe an annual   seasonal   pattern   in the   data. The   number   of   permits   issued   is substantially   higher   between April and   November.   Between   December and   March, the   number of permits   issued dropped significantly. This suggests that a   forecasting   method   incorporating   seasonality   should   perform   better than   methods   ignoring seasonality.   First, we will compare the SES,   DES,   and   TES      methods   in terms of one-month-ahead forecasts and then forecasts   for two   years   into   the   future   using   the   holdout strategy.
Part 1: One-day-ahead forecasts 
1.          (3   pts.)   Using the data   provided   in the   “Data” sheet,   calculate the   average   number   of   permits   issued each   month from   2015 to   2024.
In this   part, we will   perform. a within-sample comparison   of   SES,   DES,   and TES   based   on   how   these methods   perform. at one-month-ahead forecasting for January   2016 to   December   2022. We   leave   out   January   2015 to   December   2015 for the   initialization of TES. We   leave out January   2023 to   December      2024 for an out-of-sample comparison of the   methods;   see   Part   2   of   the   assignment. 
Note that when you are   using SES and   DES   you   can   start   forecasting   earlier than   January   2016,   but   in order to   have a fair comparison   between the thr代 写OM 252, Winter 2025 HW 3SPSS
代做程序编程语言ee   methods, we   calculate the   RMSE   only   for January 2016 to   December   2022.   We also calculate the   RMSE for January   2021 to   December   2022   as   it   gives   us   a   more   recent, and a   more   relevant,   performance   measure. 
2.          (1   pt. feasibility,   3   pts. consistency,   1   pt.   optimality)   Use the   SES   method to   calculate   the   one-   month-ahead forecasts for January   2016 to   December   2022.   Use solver to find the value   of   LS   that   minimizes the   RMSE for January   2016 to   December   2022.   Keep   LS   in the   range 0.05 to 0.95.   Report the following:
•            LS
•            RMSE for January   2016 to   December 2022
•          Forecasts   for January   2021   to   December   2022
•            RMSE for January   2021 to   December   2022
3.          (1   pt. feasibility, 3   pts. consistency,   1   pt.   optimality)   Use the   DES   method to   calculate   the   one-month-ahead forecasts for January   2016 to   December   2022.   Use solver to find the   values   of   LS   and TS that   minimize the   RMSE for January   2016 to   December   2022.   Keep   LS and TS   in the range 0.05 to 0.95.   Report the following:
•            LS, TS
•            RMSE for January   2016 to   December 2022
•          Forecasts   for January   2021   to   December   2022
•            RMSE for January   2021 to   December   2022
4.          (1   pt. feasibility, 3   pts. consistency,   1   pt. optimality)   Use   the   TES   method   to   calculate   the   one-month-ahead forecasts for January   2016 to   December   2022.   Use solver to find the values   of   LS,   TS, and SS that   minimize the   RMSE for January   2016 to   December   2012.   Keep   LS, TS,   and   SS   in         the   range 0.05 to 0.95.   Report the following:
•            LS, TS,   SS
•            RMSE for January   2016 to   December 2022
•          Forecasts   for January   2021   to   December   2022
•            RMSE for January   2021 to   December 2022
Part 2: Holdout analysis with multiple-days-ahead forecasts 
In this   part, treat January   2016 to   December   2022 as the training data   and January   2023 to   December 2024 as the   holdout   data.
5.          (5   pts.)   Use the SES   method to compute forecasts for January   2023   to   December   2024.   Use   the   value of   LS that you found   in Question   2.   Report the following:
•          Forecasts for January   2023 to   December   2024,   calculated   assuming that   the   learning   phase ends at the   end   of   December   2022
•          The   RMSE for January 2023   to   December   2024
6.          (5   pts.)   Use the   DES   method to compute forecasts for January   2023 to   December   2024.   Use the   values of   LS and TS that you found   in Question   3.   Report   the   following:
•          Forecasts for January   2023 to   December   2024,   calculated   assuming that   the   learning   phase ends at the   end   of   December   2022
•          The   RMSE for January 2023   to   December   2024
7.             (5   pts.)   Use the TES   method to compute forecasts for January   2023 to   December   2024.   Use   the   LS, TS, and SS values found   in Question 4.   Report   the   following:
•          Forecasts for January   2023 to   December   2024,   calculated   assuming that   the   learning   phase ends at the   end   of   December   2022
•          The   RMSE for January 2023   to   December   2024
8.             (For   practice and will   not   be   marked)   Based on the   analysis   you   have   done,   which   method   do   you   recommend?







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
