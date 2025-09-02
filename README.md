## Usage Rights
Dataset can be accessed here: [Indian Kids Screentime 2025](https://www.kaggle.com/datasets/ankushpanday2/indian-kids-screentime-2025)

License can be accessed here: [License](https://www.mit.edu/~amini/LICENSE.md)

## What does each row in the dataset represent?
Each row represents a different Indian child and their corresponding screen time data; since there are 9,712 entries in my dataset, the screen time data of 9,712 Indian children were observed.

## If you needed to design a class to make an object for each record, what fields would you need?
The different properties (columns) of the dataset can be used as the fields that are required to design this class.

As shown in my [UML diagram](https://docs.google.com/presentation/d/11PmIc0EbmGf_9iD4G0ZDjY7_6eSXORzoh9xcKuLTGPw/edit?usp=sharing), each object is defined by eight fields:

Int age = age of the child (8-18 years).

String gender = gender of the child (male or female).

double avg_daily_screen_time = daily average screen time in hours.

String primary_device = most frequently used screen device (i.e. TV, tablet, laptop).

boolean exceeded_rec_limit = boolean value indicating whether the child's screen time exceeds IAP (Indian Academy of Pediatrics) guidelines.

double educational_to_recreational_ratio = ratio of time spent on educational vs. recreational screen content (0.0 - 1.0).

String health_impacts = reported or likely health outcomes due to screen time (i.e. poor sleep, eye strain, anxiety).

String urban_or_rural = indicates whether the child lives in an urban or rural setting.

