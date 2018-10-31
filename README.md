# tesu_scraper
The repository to the scraper I was contracted to make in order to help Thomas Edison State University's open source materials accessibility initiative.

Thomas Edison State University (TESU) of Trenton, NJ is continuing its tradition of taking the next steps towards democratizing education.

“Identified by Forbes magazine as one of the top 20 colleges and universities in the nation in the use of technology to create learning opportunities for adults, Thomas Edison State University is a national leader in the assessment of adult learning and a pioneer in the use of educational technologies. The New York Times has stated that Thomas Edison State University is ‘the college that paved the way for flexibility.’”
https://www.tesu.edu/academics/catalog/about-tesu

TESU is a member of a network of Competency-Based Education institutions, and one of the unique opportunities TESU provides is the ability for students to demonstrate mastery before enrolling.

TESU makes available to its students, and everyone: syllabi using open source materials to teach career skills and liberal arts. Widely dispersed learning material is a familiar concept in many industries. For example, to learn Python, a student has a number of open source resources to assist in self-guided learning. TESU aims to make its courses’ contents similarly accessible, and they’re using Amazon Web Services (AWS) to deliver. I was lucky enough to have the privilege to be contracted on to help them adopt a new technology to accomplish their goals.

## How to use this repository:
The following notebooks are meant to be executed on an AWS EC2 Instance:
- 01_scraper.ipynb
- 02_check_update.ipynb	
- 03_create_sites.ipynb

For more information on how to do this, <a href = "https://medium.com/@NatalieOlivo/preserving-web-content-of-links-provided-in-a-word-doc-using-aws-services-ec2-and-s3-2c4f0cee0a26">check out my blog about it</a>. In it, I include steps for how to create IAM users, change IAM permissions, Create and Run an EC2 Instance, Configure a Jupyter Notebook on your EC2 instance, and more. Since the breadth of this blog is great and rather specific, I've created the `Python_Blogs` folder to contain more detailed examples and explanations of what all is covered.

The `Python_Blogs` folder contains a series of blogs that dive into the code contained in the above mentioned notebooks.
So far, they include the following:
- <a href = "https://github.com/nmolivo/tesu_scraper/blob/master/Python_Blogs/01_extract_from_MSWord.ipynb">01_extract_from_MSWord.ipynb</a>, a notebook that covers How to Extract Information from MS Word Documents (<a href = "https://medium.com/@NatalieOlivo/how-to-extract-data-from-ms-word-documents-using-python-ed3fbb48c122">Blog Link</a>)
