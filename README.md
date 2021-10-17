# contourf_Data0
This is a Sample Program to show that Data 0 cannot be plotted by matplotlib.pyplot(3.3.4).

Data 0 cannot be plotted by matplotlib.pyplot(3.3.4) just because some data is less than 0 (python 3.8.8).

the left-bottom area in the right figure is not colored and remains transparent just because the data z[2,2] is changed from 0 to -1.7E-13.
(see attached png file test_contourf_jet4r.png.)
