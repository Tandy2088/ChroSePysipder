# ChroSePysipder
Use Chrome+Selenium in Pyspider; Reuse a Chrome window; An example to crawl Google Patent

What is this？
1. This code is to use Chrome and Selenium in Pysipder(http://docs.pyspider.org/en/latest/) as javascript fetcher instead of its original fetcher PhantomJS. The code is based on https://www.jianshu.com/p/8d955deac99b
2. Start a new Chrome window and then re-use this window in other program.
3. A example to crawl Google Patent using Chrome+Selenium+Pyspider.

Why use this?
1. Chrome+Selenium may be more versatile than PhantomJS which is not updated.
2. Start a new Chrome window and then login any website mannully. After that, we re-use this window to crawl website meaning we do not need to worry about the login anymore. We can also interact with this window anytime. The re-using of window also have a disadvantage, we can only crawl websites one by one meaning the speed is low.

How to use?
1. Make sure that the Chrome webdrive, Selenium, Pyspider and Flask are corrected installed.(I use Anaconda Python 2.7 in Win10)
