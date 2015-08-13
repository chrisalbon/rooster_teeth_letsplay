# Data On 990 Let's Play Videos

It was created by scraping the metadata on the 990 YouTube videos on Roosterteeth's Let's Play channel.
The data and script will be avaliable on GitHub (a online repository of code) once I add some comments to my code (bad me... bad!).

Most of the variables are pretty straightforward, however one required a quick explanation. The cast member variables (e.g. "Lindsey", "Gavin" etc..) were created counting the number of video descriptions where that cast member appears. If a cast member appears in a show's description, the variable is labeled "True", if they are not: "False." This mostly works because, luckily, often the description mentions each of the cast members present in the video by name (e.g. "This week Gavin and Michael fight it out...") but that is not always the case. Therefore, these variables are imperfect, but better than nothing.