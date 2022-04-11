# School_District_Analysis
The school board has notified us that the files show evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We have been tasked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, then repeat the school district analysis. The results of the removal will appear as follows in the grade summaries:
![Image of 9th Grade Removed Data](<./resources/removed_ths_grade_9_results.png>) 

## Data Changes After Cleanup
- How is the district summary affected?
    ![Image of Pre-Adjusted District Summary](<./resources/unclean_district_data.png>) 
    Above is the "unclean" data. The district summary shows a tenth of a percent drop between the average passing percentages when looking at the adjusted data below. 
    ![Image of Adjusted District Summary](<./resources/adjusted_district_data.png>)
    
- How is the school summary affected?
    ![Image of Pre-Adjusted School Summary](<./resources/unclean_school_summary.png>)
    Above is the "unclean" data. We show a ~30% increase in both reading and math scores for Thomas High School, moving them further into the well-performing section when we look at the adjusted data below. 
    ![Image of Adjusted School Summary](<./resources/adjusted_school_summary.png>)
    
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    As seen above, we see a significant improvement after replacing the data that was falsified.
    
- Replacing the ninth-grade scores affected the following: 
 1) Math and reading scores by grade were not affected for any other school.
 2) Scores by school spending were unaffected.
 3) Scores by school size were unaffected.
 4) Scores by school type were unaffected.
 
## Summary
The scores for Thomas High School were significantly improved when removing the 9th grade data. This indicated a likely falsification of failure rate for the 9th graders at said school. The district in general did not note much difference for any other school. Thomas High School moved further into the well-performing section, but there was little to note within the summaries for spending, size, or type of school. 