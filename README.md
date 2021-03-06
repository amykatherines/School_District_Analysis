# PyCity Standardized Testing Analysis

## Overview

PyCity schools asked for an analysis of the latest standardized testing results.  The initial request from the schools was for all data to be summarized into the following resultsets:

* District Wide Results
* School Specific Results
* Math & Reading scores evaluated by
  * Grade
  * School Spending
  * School Size
  * School Type
  
The initial results and data provided created concerns that there was possible academic dishonesty in the Thomas High School (THS) 9th grade test scores. The school requested to see all the results without the THS 9th grade included in the averages and percentages. The following analysis is a discussion of how the results were impacted when the subset was removed.

## Results

Below we will present both sets of results to show the impact of removing the THS 9th graders.  

### District Summary

The comparison of District metrics shows a slight decrease in the districts Math scores (.1 point) and passing percentages (.1-.2%) when THS 9th graders are removed.  The reading score was unaffected.

*All Students*     
![All Students District Summary](Resources/district_summary.png)

*Thomas High 9th Grade Students Removed*  
![THS 9th Removed District Summary](Resources/district_summary_THS9_removed.png)

### School Summary

As seen below, when comparing Thomas High School results specifically, we see a similar slight decrease in Math scores and percent passing in Math and Reading. However, **reading scores improved** when the suspected dishonest grades were removed.    

The results below are sorted on overall percentage passing which reveals that the school rankings did not change when the suspect grades were removed.  

*All Students*     
![All Students School Summary](Resources/school_summary_sorted_overall_passing.png)

*Thomas High 9th Grade Students Removed*  
![THS 9th Removed School Summary](Resources/school_summary_sorted_overall_passing_THS9_removed.png)

### Grade Level Results

When the dataset is created for the school/grade-level view on Reading and Math scores, the 9th Grade THS value is now "nan" for the second set of data analyzed.  "nan" indicates that there is no values to be evaluated for that cross-section.

*Math - All Students (left); Thomas High 9th Grade Students Removed (right)*  
![All Students Math Grade Level Results](Resources/school_math_by_grade.png) ![THS 9th Removed Math Grade Level Results](Resources/school_math_by_grade_THS9_removed.png)


*Reading - All Students (left); Thomas High 9th Grade Students Removed (right)*  
![All Students Reading Grade Level Results](Resources/school_reading_by_grade.png) ![THS 9th Removed Reading Grade Level Results](Resources/school_reading_by_grade_THS9_removed.png)

### Scores by School Spending

To analyze the affects of per student spend on test results, we divided schools into 4 spending buckets.  Thomas High School spends $638 per student.  This puts them in the third spending bucket ($630-$644).  When combined with the other schools in this range, the results when rounded remain the same with or without the THS 9th grade students (if we presented more precision on the results, they would show slight differences in results).

*All Students*
![All Students Spending](Resources/spending_ranges.png) 

*Thomas High 9th Grade Students Removed*
![THS 9th Removed Spending](Resources/spending_ranges_THS9_removed.png)

### Scores by School Size

Like we saw with the School Spending analysis, the results for the school size comparison are the same with or without the 9th Grade THS grades.  If more precision was shown, there would be some difference in the Medium Sized schools which THS is a part of.  

*All Students*                  
![All Students](Resources/school_size.png) 

*Thomas High 9th Grade Students Removed*
![THS 9th Removed](Resources/school_size_THS9_removed.png)

### Scores by School Type

The average scores and passing percentages based on School Type remain the same for when 9th Grade THS grades are removed.  If more precision were shown, there would be slight differences in the Charter school statistics.

*All Students*                  
![All Students School Type](Resources/school_type.png) 

*Thomas High 9th Grade Students Removed*
![THS 9th Removed School Type](Resources/school_type_THS9_removed.png)

## Summary

As discussed, the PyCity standardized test results without Thomas High School's 9th grade had changed in the following ways:

1. District level average math scores were .1 point lower
2. District level percent passing math was  .2% lower
3. District level percent passing reading was .1% lower
4. District level percent overall passing was .3% lower
5. Thomas High School math scores, percent passing math, reading and overall were all lower after removing 9th graders
6. Thomas High school average reading test score improved when the 9th grade scores were removed


