# Date Validation Regex

Regex : ```([0-2][0-9]|[3][01])/([0-9]|[1][0-2])/([12].{2}[0-9])```

* Regex Date Range: ```From 01 To 31```
* Regex Month Range: ```From 1 To 12```
* Regex Year Range: ```From 1000 To 2999```

More About This Date Validation Regex

* Made By: Krishna Wadhwani

* Date Of Invention: 7/December/2021

# Java Implementation

```
public class DateValidationRegex {
    public static void main(String[] args){
        // Date
        String Date = "31/12/2007";
        // Regex
        String regex = "([0-2][0-9]|[3][01])/([0-9]|[1][0-2])/([12].{2}[0-9])";
        // Using String Method ".matches()" To Match Date(String) With Regex(String regex)
        boolean isDateOrNot = Date.matches(regex);
        // Printing: isDateOrNot(boolean)
        System.out.println(isDateOrNot);
    }
}
```
