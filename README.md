# nickCLIP
generating nickname using profile img and description

## Twitter(X)에서 데이터 크롤링 하는법

requirements: python 3.10 or higher

1. installing twscrape
~~~
pip install twscrape
~~~

2. enter to work directory
~~~
cd crawl
~~~

3. at crawl/ directory make accounts.txt file with the type of
> twitter_id:twitter_pwd:twitter_email:twitter_email_pwd

4. account activate
~~~
twscrape add_accounts accounts.txt username:password:email:email_password
~~~
