# Getting Started with ptg-react

### Install the package

`npm i ptg-react`

## Components available in this package

1. **Calendar**

   _Import calendar_

   `import {PtgUiCalendar} from 'ptg-react;`

   _Properties_

   **The " ? " represents here that this property is optional**

   > onChange?: any;  
   > date?: any;  
   > selected?: any;  
   > className: any;  
   > startDate?: any;  
   > endDate?: any;  
   > disabled?: boolean;  
   > startRef?: any;  
   > onKeyDown?: any;  
   > accessKey?: string;

2. **Charts**

   - D3 Charts  
     **Import charts**  
     `import { PtgUiD3Line, PtgUiD3Bar, PtgUiD3Pie } from "ptg-react";`

     1. Bar chart  
        _Properties_  
         **The " ? " represents here that this property is optional.**
        **Data array must contain color property for its color in chart.**
        > data?:any,  
        > height?:any,  
        > width?:any,  
        > source?:any,  
        > title?:any,  
        > x_title:string,  
        > y_title:string,  
        > start?:any,  
        > end?:any
     2. Line chart  
         _Properties_  
         **The " ? " represents here that this property is optional.**

        > data:any,  
        > height:any,  
        > width:any,

     3. Pie chart  
        _Properties_  
         **The " ? " represents here that this property is optional.**
        > data: any;  
        > height?: any;  
        > width?: any;  
        > innerRadius?: any;  
        > outerRadius?: any;  
        > colorsArray?: any;

   - HighCharts

     - 2D  
       **Import charts**  
       `import { PtgUiColumn, PtgUiPie,PtgUiLine,PtgUiLineBar,PtgUiStackedColumn } from 'ptg-react';`

       1. Column chart  
           _Properties_  
           **The " ? " represents here that this property is optional.**

          > remainingOptions:any,  
          > highcharts?:any,  
          > title?:any,  
          > data?:any

       2. Line chart  
           _Properties_  
           **The " ? " represents here that this property is optional.**
          > remainingOptions:any,  
          > highcharts?:any,  
          > title?:any,  
          > data?:any
       3. Linebar chart  
          _Properties_  
          **The " ? " represents here that this property is optional.**

          > remainingOptions:any,  
          > highcharts?:any,  
          > title?:any,  
          > subtitle?:any,  
          > categories?:any

       4. Pie chart  
           _Properties_  
           **The " ? " represents here that this property is optional.**

          > remainingOptions:any,  
          > highcharts?:any,  
          > title?:any,  
          > data?:any

       5. Stacked Column chart  
           _Properties_  
           **The " ? " represents here that this property is optional.**
          > remainingOptions:any,  
          > highcharts?:any,  
          > title?:any,  
          > data?:any,  
          > yTitle?:any,  
          > categories?:any

     - 3D  
       **Import charts**  
       `import { PtgUiColumn, PtgUiPie,PtgUiLine,PtgUiLineBar,PtgUiStackedColumn} from 'ptg-react';`

       1. Column chart  
           _Properties_  
           **The " ? " represents here that this property is optional.**

          > remainingOptions:any,  
          > highcharts?:any,  
          > title?:any,  
          > data?:any,  
          > categories?:any,  
          > xTitle?:any,  
          > yTitle?:any

       2. Line chart  
           _Properties_  
           **The " ? " represents here that this property is optional.**

          > remainingOptions:any,  
          > highcharts?:any,  
          > title?:any,  
          > data?:any,  
          > categories?:any,  
          > xTitle?:any,  
          > yTitle?:any

       3. Pie chart  
           _Properties_  
           **The " ? " represents here that this property is optional.**
          > remainingOptions:any,  
          > highcharts?:any,  
          > title?:any,  
          > data?:any,  
          > categories?:any,  
          > seriesName?:any,

3. **Data Table**

   - Ag grid  
      **Import Ag Grid**  
      `import { PtgUiAgGrid } from 'ptg-react';`
     _Properties_  
      **The " ? " represents here that this property is optional.**

     > data:any[],  
     > autoGroupColumnDef:any,  
     > columnDefs:any,  
     > defaultColDef:any,  
     > rowSelection?:string,  
     > groupSelectsChildren?:boolean,  
     > pagination?:boolean,  
     > paginationPageSize?:number,  
     > customPagination?: boolean,  
     > domLayout?:any

   - React table  
      **Import React Table**  
      `import { PtgUiReactTable } from 'ptg-react';`
     _Properties_  
      **The " ? " represents here that this property is optional.**
     > data?:any;  
     > columns?:any;

4. **Download file**
   **Import Download**  
   `import { PtgUiDownload } from 'ptg-react';`
   _Properties_  
   **The " ? " represents here that this property is optional.**
   > columns?: any;  
   > dataToDownload?: any;  
   > allowFileTypes?: any;

- Formats
  1. PDF
  2. Word
  3. Image
  4. Excel

5. **Indeterminate Checkbox**
   **Import Indeterminate Checkbox**  
   `import { PtgUiIndeterminateCheckbox } from 'ptg-react';`
   _Properties_
   > items:any;
6. **Input**  
   **Import input**  
   `import { PtgUiInput } from 'ptg-react';`
   _Properties_  
   **The " ? " represents here that this property is optional.**
   > type: string;  
   > value?: any;  
   > onChange?: any;  
   > placeholder?: string;  
   > disabled?: boolean;  
   > required?: boolean;  
   > className?: string;  
   > inputsize?: string;  
   > name?: string;  
   > onBlur?: any;  
   > ref?: any;  
   > maxlength?: any;  
   > onKeyUp?: any;  
   > id?: string;
7. **loader**  
   **Import Loader**  
   `import { PtgUiLoading } from 'ptg-react';`
8. **Multi Select**  
   **Import Multi Select**  
   `import { PtgUiMultiSelectbox } from 'ptg-react';`  
   _Properties_  
   **The " ? " represents here that this property is optional.**
   > name?: string,  
   > selectedValues?: any,  
   > id?: string,  
   > className?:string,  
   > list: { value: any, label: any }[],  
   > showCheckbox?: boolean,  
   > placeholder?:string  
   > singleSelect?: boolean,  
   > onSelect?:any,
9. **Radio**  
   **Import Radio**  
   `import { PtgUiRadio } from 'ptg-react';`  
   _Properties_  
   **The " ? " represents here that this property is optional.**

   > name?: string;  
   > value?: string;  
   > id?: string;  
   > htmlFor?: string;  
   > onChange?: (event: React.ChangeEvent<HTMLInputElement>) => void;  
   > list: { id: string; name: string; value: string }[];  
   > children?: React.ReactNode;  
   > checked?: boolean;  
   > accessKey?: string;

10. **Select**  
    **Import Select**  
    `import { PtgUiSelect } from 'ptg-react';`  
    _Properties_  
    **The " ? " represents here that this property is optional.**

    > name?: string;  
    > value?: string;  
    > id?: string;  
    > className?: string;  
    > list: { label: any; value: any }[];  
    > onBlur?: any;  
    > htmlFor?: string;  
    > onChange?: (event: React.ChangeEvent<HTMLInputElement>) => void;

11. **Text Area**  
    **Import Text Area**  
    `import { PtgUiTextArea } from 'ptg-react';`  
    _Properties_  
    **The " ? " represents here that this property is optional.**

    > value?: any;  
    > onChange?: any;  
    > placeholder?: string;  
    > disabled?: boolean;  
    > hasError?: boolean;  
    > onFocus?: any;  
    > dataTest?: string;  
    > required?: boolean;  
    > className?: string;  
    > inputsize?: string;  
    > name?: string;  
    > onBlur?: any;  
    > ref?: any;  
    > rows?: any;  
    > cols?: any;  
    > form?: any;  
    > maxlength?: any;  
    > onKeyUp?: any;  
    > id?: string;

12. **Alert**  
    **Import Alert**  
    `import { PtgUiAlert } from 'ptg-react';`  
    _Properties_  
    **The " ? " represents here that this property is optional.**

    > message?: any;
    > type?: any

13. **Check box**  
    **Import Check box**  
    `import { PtgUiCheckbox } from 'ptg-react';`  
    _Properties_  
    **The " ? " represents here that this property is optional.**

    > id?: string;
    > name?: string;
    > label?: string;
    > value?: string;
    > for?: string;
    > htmlFor?: string;
    > checked?: boolean;
    > onChange?: (event: React.ChangeEvent<HTMLInputElement>) => void;
    > className?: string;
    > accessKey?: string;

14. **Accordian**  
    **Import Accordian**  
    `import { PtgUiAccordian } from 'ptg-react';`  
    _Properties_  
    **The " ? " represents here that this property is optional.**

    > stories:any

15. **Pipes**  
    **Import Pipes**  
    `import { capitalizeFirstLetter, inrFormat, truncateString, phoneNumber, convertIntoPhoneNumber } from 'ptg-react';`  
    _Properties_  
    **The " ? " represents here that this property is optional.**
