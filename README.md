Title: Predicting Variation in Daily Martian Atmospheric Temperature Using Machine Learning Techniques

Data Source: https://www.emiratesmarsmission.ae/

This dissertation source presents the findings of a study that explores the use of machine learning techniques to predict variation in daily Martian atmospheric temperature. According to research and explorations conducted on Mars, it was believed that the planet once supported life. This resulted from evidence indicating the presence of water and a thick warm atmosphere on Mars in the past, making the red planet an intriguing target for exploration. As technological tools have evolved with advancements in science and technology, machine learning has become an essential technical tool for Mars exploration.

This study focuses on the use of machine learning techniques to analyze Mars' weather patterns for possible habitation of life. The study relied on data obtained from the Emirates Mars Mission (EMM) datasets, specifically the EMM EMIRS instrument database. Various techniques such as exploration, preprocessing, model development, and evaluations were performed on the dataset to predict the variation in daily atmospheric temperatures on Mars.

The study developed seven machine learning models, including Random Forest, Linear Regression, Support Vector Machine (SVM), Artificial Neural Network (ANN), Convolutional Neural Network (CNN), Lasso Regression, and Decision Tree. The developed models were subjected to hyperparameter fine-tuning to improve their accuracies. Finally, each model was evaluated using evaluation techniques such as Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and R-squared (R2) value.

The results showed that Random Forest outperformed all other six models used in this work, with scores as follows: RMSE = 1.5525, MSE = 2.4105, MAE = 1.1939, and R2 = 0.8283. The scores obtained were visualized to aid in understanding and interpreting the results. Overall, this study demonstrates the effectiveness of machine learning techniques in predicting temperature variation on Mars, providing important implications for future missions to the red planet. This dissertation source includes detailed information on the study's methodology, data analysis, and key findings, as well as recommendations for future research and practical applications.

This study was conducted as part of a Masters degree in big data science and technology and submitted to the University of Bradford, Faculty of Engineering and Informatics, as a requirement for the completion of the degree program.

Data Description:
sclk: The spacecraft clock time in seconds
sclk_sub: A sub-clock count in units of 1/91,250 seconds
det_num: The number of the detector used for the measurement
target_type_num: A numerical code identifying the target type
utc: The Coordinated Universal Time of the measurement
incidence: The angle between the incidence angle and the target surface normal in degrees
emission: The angle between the emission angle and the target surface normal in degrees
phase: The angle between the incidence and emission angles in degrees
bore_flag: A flag indicating whether the bore-sight of the instrument was used
nfov: The angle subtended by the narrow field of view of the instrument in degrees
scan_period: The period of the instrument's scan in seconds
ra: The right ascension of the target in degrees
dec: The declination of the target in degrees
x2d: The x-coordinate of the target in the instrument's 2D image
y2d: The y-coordinate of the target in the instrument's 2D image
npts2d: The number of points used in the 2D image
temp: The temperature of the target in Kelvin
shift: The shift of the target in the instrument's 2D image
tsurfco2: The surface temperature of the target in Kelvin
chi2temp: The chi-squared value for the temperature fit
pres0: The pressure at the target in Pascals
taudust: The dust optical depth

Developer Tools:
Programming Language: Python
IDE: Vscode & Colab
GUI: wxPython, wxFormBuilder
Web Scraping: BeautifulSoup, ParseHub
Debugging & Testing: Jupyter Notebook
Data Format: Microsoft Excel

