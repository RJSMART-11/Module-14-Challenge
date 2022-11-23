### Module 14 Challenge ###

# Algrotimic Trading #

We were asked to anaylze our actual reutrns anaginst our strateggy to so how succesful it was, and also to see if we could come up with a more profitable strategy.

Below are the results as follows;

# Baseline: #

![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/Resources/PNG/Baseline_report.png)
![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/Resources/PNG/Baseline_returns%20plot.png)
![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/Resources/PNG/Baseline_returns.png)

After running an analysis of our orignal stategy compared to our actual gains, it appears that our actual reuturns were pretty similar to our to our stategy, so much so that they both have almost identical trend-lines interms of direction of returns throughout the entire period. Although after analysis we can see that the orginal strategy outpreformed our actual returns.

# Adjusted Test/training periods to 6 months: #

![[Images/adjust_train_test_period_6_months_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/Resources/PNG/adjust_train_test_period_6_months_report.png)
![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/Resources/PNG/adjust_train_test_period_6_months_returns.png)
![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/Resources/PNG/adjust_train_test_period_6_months_returns_plot.png)

After running an analysis of our adjusted test/training period stategy compared to our actual gains, it appears that our actual reuturns were somewhat similar to our to new stategy. This time around we noticed our stategy go steady with and then fall under our actual returns during the time between 2019-early 2021, followed by a very steep increase in our our new strategy's returns out preforming our actual returns by a substanial amount by the end of 2021. Due to the final outcome of this analysis we can determine that new stategy ended up being very profitable.


# Adjusted SMA windows(short - 12, long - 150): #

![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/Resources/PNG/adjusted_SMA_windows_12_150_accurracy_report.png)
![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/Resources/PNG/adjusted_SMA_windows_12_150_plot.png)
![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/Resources/PNG/adjusted_SMA_windows_12_150_returns.png)

After running an analysis of our adjusted SMA window stategy compared to our actual gains, it appears that our actual reuturns outpreformed our strategy. This time around we noticed our stategy go steady with our actual reuturns up until around sept 2022 then fall under our actual returns during the time between 2019 -2021, and failing to the rise greater than our actual returns. Due to the final outcome of this analysis we can determine that Adjusted SMA window stategy ended up being less profitable than our actual returns.


Next we will run the orignal baseline data through a logestic regression model. At that point we will then analysis how the new model impacted the reutrns.

# Logestic Regrression Model Results: #
After the running through the anaylis we can see that our orignal baseline model out preformed the logestic regression model by the end of the time period even with the 'LRM' taking a pretty big dip need the end of 2021. 

![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/LRM%20Report.png)
![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/LRM%20Returns.png)
![[Images/Baseline_report.png]](https://github.com/RJSMART-11/Module-14-Challenge/blob/main/LRM%20plot.png)


## Conclusion: ##
After analzing all the different strategies we can determine that the Adjusted Test/training periods to 6 months: strategy had the greatest returns.



