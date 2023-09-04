# My resume 

This is my resume.  
The template of this project was forked from ['jglovier/resume-template'](https://github.com/jglovier/resume-template).  

## Running locally  

To test locally, run the following in your terminal:  

1. `cd /PATH/TO/LOCAL_REPO/`  
1. `bundle install`  
2. `bundle exec jekyll serve --port <your_port_number>`  
3. Open the page in your browser.  

## Customizing  

Where to modify name and sections to include: `_config.yml`  
Where to modify contens in each section:  

```
_data/
├── associations.yml
├── education.yml
├── experience.yml
├── interests.yml
├── links.yml
├── presentations.yml
├── publicaions.yml
├── recognition.yml
└── skills.yml
```

Most of the content configuration will take place in the `/_layouts/resume.html` file. Simply edit the markup there accordingly.  
