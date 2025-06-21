# PROJECT-2-IN-THE-WORKING
This includes the things learned and executed before working on the 2nd SQL project.
## FIRST LESSON: PIVOTING
* Concept of CASE STATEMENT
* Applying CASE STATEMENTS In Calculating:
   * Sum
   * Avg
   * Min, Max
   * Median (percentile)
* Using Advanced Segementation to Categorize Revenue Values into Tiers based on High, Low and Medium Percentiles.

## SECOND LESSON: DATE
* Used various date manipulating functions:
   * DATE_TRUNC()
   * TO_CHAR()
   * DATE_TYPE
   * CURRENT_DATE
   * INTERVAL ''
   * and my favourite, EXTRACT( )
## THIRD LESSON: WINDOW FUNCTION
 Leanrned How to use WINDOW FUNCTIONs and used them in several examples:
### PART 1: BASICS (including using SUBQUERY and CTEs)
  * AVG() OVER(PARTITION BY)
  * SUM() OVER(PARTITION BY)
  * ROW_NUMBER() OVER(PARTITION BY ORDER BY)
### PART 2: COHORT ANALYSIS
   * MIN() OVER(PARTITION BY)
   * COUNT() OVER(PARTION BY)
   * AVG() OVER(PARTITION BY) - FOR CUSTOMER/AVERAGE LIFETIME VALUE (LTV,ATV)
### PART 3: Advance use of WINDOW FUNCTIONs to:
  * Calculate - Running Order Count And Running Average Revenue with ORDER BY
  * Find - ROW_NUMBER(), RANK(), DENSE_RANK()
  * Find - FIRST_VALUE(), LAST_VALUE(), NTH_VALUE()
  * Calculate LAG(), LEAD()
  * Find - Month Over Month and YEAR OVER YEAR Growth using LAG()
  * Implement FRAME CLAUSES - ROWS AND CURRENT ROW
  
