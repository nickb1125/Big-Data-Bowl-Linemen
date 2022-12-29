# Big-Data-Bowl-Linemen

Many current assessments of defensive linemen rely on the simple number of individual disruptions (i.e., sack, hurry, etc.) that a lineman records. While this is simple to compute, it doesn’t really show us much of the full picture. Sure, such numbers might tell us who has the most highlight hits on their resume, but they give us little perspective on what linemen are helping their team the most overall. Put more bluntly, it undervalues the "playmakers" of the defensive line. Any defensive linemen can reach the quarterback when unblocked, and similarly any defensive linemen that draws a double block every play can be stunted. What is imminently important is not necessarily who draws the most pressure or the most sacks, but instead who helps his team's chances of play disruption most, given where on the field he is and how many blockers are present.
This project introduces the Instantaneous Disruption Probability Increase (IDPI) metric, which measures differences in performance of pass rushers compared to other lineman in similar situations. A linemen’s ability to improve his team's probability of play disruption is used as the standard for performance. The IDPI metric is centered around the idea that, on any given play, a rusher improves, or hurts, his entire line’s chance of achieving a pass disruption by some probability. This probability, if intuitively estimated, can serve as an measurement of how effective a defensive linemen is.

# Code Instructions

1. Run code/clean/clean.ipynb to import spatial linemen data, clean, and organize into master_track object class. This will populate data folder with a .pkl object class full of data.
2. Run code/modeling/lstm_training.ipynb to train and save LSTM model weights into data folder
3. Run code/plotting/data_exporter.ipynb to export (1) plotting data and (2) ranking order for linemen
4. Run code/plotting/plotting.Rmd to complete plotting
