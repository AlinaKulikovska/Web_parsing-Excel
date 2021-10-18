# Web_parsing-Excel

I have task to parse ecxel file from web site http://www.ukrstat.gov.ua/ , that can be found by "статистична інформація -> Сільське, лісове та рибне господарство -> Обсяг виробництва, урожайність та зібрана площа сільськогосподарських культур за їх видами" and transform it to table like:

1.date - 1 January year of excel file;

2.dateRelease - current date;

3.shapeId - name of region;

4.comdty - name of crop;

5.param - name of parameter;

6.value - meaning of parameter.

And the necessary sheets in document are 6-25,30,31,38,39,45,46. All results you can see in file 'Web parsing and .xls file.ipynb'
