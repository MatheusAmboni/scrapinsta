# ScrapInsta
A script to scraping data from Instagram
## Install
First of all you can run:
<pre>pip install scrapinsta</pre>
After that you need to install these requirements:
<ul>
  You can install one-by-one:
  <li>selenium
  <pre>pip install selenium</pre></li>
  <li>webdriver_manager
  <pre>pip install webdriver_manager</pre></li>
  <li>cryptography
  <pre>pip install cryptography</pre></li>
  Or install by requirements.txt
  <li><pre>pip install -r requirements.txt</pre></li>
</ul>

## Scraping user followers

### Usage
<ol>
  <li>from scrapinsta import <b>Scrapinsta</b> and instantiate</li><br>
  <li>Call function Scrapinsta.<b>get_user_follower(account, amount, method, print_followers)</li></b>
</ol>
<ul>
  <br> <b>account</b>: Account which want to get user followers
  <br> <b>amount</b>: Number of followers to scraping 
  <br> <b>method</b>: By default is 'list'(returns a list), but can be 'txt' this will write a .txt with user followers
  <br> <b>print_followers</b>: By default is 'false'(don't print followers), but can be 'true' this will print followers
  <br><br>Example code:<br>
  <pre> 
    from scrapinsta import Scrapinsta<br>
    account = 'nasa' # Account to get info
    amount = 50 <br>
    # Instantiate Scrapinsta
    s = Scrapinsta()<br>
    # Testing: method = 'list'
    list_followers = s.get_user_followers(account, amount, method='list', print_followers='true')<br>
    # Testing: method = 'txt'
    s.get_user_followers(account, amount, method='txt', print_followers='true')
  </pre>
</ul>

## Scraping user following account

### Usage
<ol>
  <li>from scrapinsta import <b>Scrapinsta</b> and instantiate</li><br>
  <li>Call function Scrapinsta.<b>get_user_followings(account, amount, method, print_following)</li></b>
</ol>
<ul>
  <br> <b>account</b>: Account which wants to get followed users 
  <br> <b>amount</b>: Number of followed users to scraping 
  <br> <b>method</b>: By default is 'list'(returns a list), but can be 'txt' this will write a .txt with followed users
  <br> <b>print_following</b>: By default is 'false'(don't print followed users), but can be 'true', this will print followed users
  <br><br>Example code:<br>
  <pre> 
    from scrapinsta import Scrapinsta<br>
    account = 'nasa' # Account to get info
    amount = 50 <br>
    # Instantiate Scrapinsta
    s = Scrapinsta()<br>
    # Testing: method = 'list'
    list_following = s.get_user_followings(account, amount, method='list', print_following='true')
    # Testing: method = 'txt'
    s.get_user_followings(account, amount, method='txt', print_following='true')
  </pre>
</ul>

## Contact:  

<a href="https://www.linkedin.com/in/matheuskolln"><img src="https://icons-for-free.com/iconfiles/png/512/linked+linkedin+logo+social+icon-1320191784782940875.png" width="16"></img></a> [LinkedIn](https://www.linkedin.com/in/matheuskolln)  

<a href="https://twitter.com/matheuskolln"><img src="https://cdn2.iconfinder.com/data/icons/metro-uinvert-dock/256/Twitter_NEW.png" width="16"></img></a> [Twitter](https://twitter.com/matheuskolln)   

<a href="https://www.instagram.com/1matheus4/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Instagram-Icon.png/1025px-Instagram-Icon.png" width="16"></img></a> [Instagram](https://www.instagram.com/1matheus4)  

<a href="mailto:matheuzhenrik@gmail.com"><img src="https://d1nhio0ox7pgb.cloudfront.net/_img/o_collection_png/green_dark_grey/256x256/plain/mail.png" width="16"></img></a> [E-mail](mailto:matheuzhenrik@gmail.com)  


