# instaBot - bot for likes and following

Welcome to the instaBot. InstaBot is bot created and coded in Python 3.8, with some addons. Addons which are used in this small project are selenium and panda. 

## Instractions:
For futhur edit this are instructions:

Login button: 
  `button_login = webdriver.find_element_by_css_selector('#react-root > section > main > div > article > div > div:nth-child(1) > div > form > div:nth-child(4) > button')`
  
Thumbnail:
  `first_thumbnail = webdriver.find_element_by_xpath('//*[@id="react-root"]/section/main/article/div[1]/div/div/div[1]/div[1]/a/div')`

Username text:
  `username = webdriver.find_element_by_xpath('/html/body/div[4]/div[2]/div/article/header/div[2]/div[1]/div[1]/h2/a').text`

Follow button:
  `webdriver.find_element_by_xpath('/html/body/div[4]/div[2]/div/article/header/div[2]/div[1]/div[2]/button').click()`

Like button:
  `button_like = webdriver.find_element_by_xpath('/html/body/div[4]/div[2]/div/article/div[2]/section[1]/span[1]/button')`

## Likes and follows:

All likes and follows are saving in csv file, this kind of saving is made because maybe some how in future user will decide to make some kind of render on his private website for statistic.

### Thanks for downloading and using instaBot.
