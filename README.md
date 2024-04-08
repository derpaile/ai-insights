AI-Generated News Articles
This project demonstrates the use of OpenAI's GPT-4 language model and DALL-E-3 image generation model to create a website with AI-generated news articles on user-specified topics. The articles include a clickbait-style headline, a detailed article content, a main image, and user comments.
Features
User-specified topics for news article generation
Clickbait-style headlines generated using GPT-4
Detailed article content generated using GPT-4
Main article image generated using DALL-E-3
User comments with generated author profiles
Archive page displaying previously generated articles sorted by creation time
Responsive design using Bootstrap and custom CSS
Social sharing links for each article
Favicon support
Prerequisites
Python 3.7 or higher
OpenAI API key
Installation
Clone the repository:
bash

Copy code
git clone https://github.com/derpaile/Postillian.git
Change into the project directory:
bash

Copy code
cd ai-generated-news-articles
Install the required dependencies:
bash

Copy code
pip install -r requirements.txt
Create a keys.py file in the project root and add your OpenAI API key:
python

Copy code
openai_key = "YOUR_API_KEY"
Usage
Run the script:
bash

Copy code
python main.py
Enter a topic for the news article when prompted, or press Enter to finish generating articles.
The generated articles will be saved in the archive directory, and an index.html file will be created in the project root, linking to all the generated articles.
Open the index.html file in a web browser to view the generated news article website.
Customization
Modify the generate_text function to customize the article generation prompts and parameters.
Adjust the generate_image function to change the image generation parameters.
Customize the HTML templates in the create_webpage and create_archive_index functions to change the website's appearance and layout.
Replace the favicon.ico file in the project root with your own favicon.
License
This project is open-source and available under the MIT License.
Acknowledgements
OpenAI for providing the GPT-4 and DALL-E-3 models.
Bootstrap for the responsive CSS framework.
Font Awesome for the icons used in the website.
Disclaimer
The content generated by this project is solely based on the AI models' outputs and may not reflect real-world events or opinions. The generated articles are for demonstration purposes only and should not be considered as factual news articles.
# ai-insights
# ai-insights
