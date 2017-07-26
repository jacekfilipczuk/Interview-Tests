# Helping Recruiters - Classification Task

There is a need to improve the user experience of recruiters using the website. Currently there are many actions a recruiter must do to post a job on to the site.

Recruiters have provided us feedback that it takes them too long to post a job on our site. They have told us that it would be good if we could pre-fill, or infer the value of some fields on the job posting web page based on what we already know about the job. 

A concrete example of this would be for us to automatically pre-fill the job sector field based on the current job title and job description which has already been entered by the user.

So, for this task we would like you to create a solution which can classify textual input (e.g. the job title and description) and output the most likely job sector that matches this input. 

You will be provided with a CSV file containing a raw collection of job titles, descriptions split over 6 sectors (industries). You should use the provided data to construct both your training and test data sets. We recommend using a 80/20 train/test split. 

