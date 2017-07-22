ktamg2@1b6946be137d:~$ mkdir wget-activehistory
ktamg2@1b6946be137d:~$ cd  wget-activehistory
ktamg2@1b6946be137d:~/wget-activehistory$ wget http://activehistory.ca/papers/
--2017-07-22 22:11:59--  http://activehistory.ca/papers/
Resolving activehistory.ca (activehistory.ca)... 138.197.156.41
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘index.html’
    [ <=>                                                                                                ] 53,041      --.-K/s   in 0s      
2017-07-22 22:11:59 (175 MB/s) - ‘index.html’ saved [53041]
ktamg2@1b6946be137d:~/wget-activehistory$ -r
-bash: -r: command not found
ktamg2@1b6946be137d:~/wget-activehistory$ wget [options] [URL]
http://[options]: Invalid IPv6 numeric address.
http://[URL]: Invalid IPv6 numeric address.
ktamg2@1b6946be137d:~/wget-activehistory$ ls
index.html
ktamg2@1b6946be137d:~/wget-activehistory$ wget -r --no-parent -w 2 --limit-rate=20k http://activehistory.ca/papers/
--2017-07-22 22:17:53--  http://activehistory.ca/papers/
Resolving activehistory.ca (activehistory.ca)... 138.197.156.41
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/index.html’

    [       <=>                                                                                          ] 53,041      20.6KB/s   in 2.5s   

2017-07-22 22:17:55 (20.6 KB/s) - ‘activehistory.ca/papers/index.html’ saved [53041]

Loading robots.txt; please ignore errors.
--2017-07-22 22:17:57--  http://activehistory.ca/robots.txt
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 162 [text/plain]
Saving to: ‘activehistory.ca/robots.txt’

100%[===================================================================================================>] 162         --.-K/s   in 0s      

2017-07-22 22:17:58 (15.3 MB/s) - ‘activehistory.ca/robots.txt’ saved [162/162]

--2017-07-22 22:18:00--  http://activehistory.ca/papers/themes
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/themes/ [following]
--2017-07-22 22:18:02--  http://activehistory.ca/papers/themes/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes’

    [       <=>                                                                                          ] 44,187      20.0KB/s   in 2.2s   

2017-07-22 22:18:04 (20.0 KB/s) - ‘activehistory.ca/papers/themes’ saved [44187]

--2017-07-22 22:18:06--  http://activehistory.ca/papers/indigenous-histories/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/indigenous-histories/index.html’

    [       <=>                                                                                          ] 48,707      20.0KB/s   in 2.4s   

2017-07-22 22:18:09 (20.0 KB/s) - ‘activehistory.ca/papers/indigenous-histories/index.html’ saved [48707]

--2017-07-22 22:18:11--  http://activehistory.ca/papers/refugees-in-historical-perspective/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/refugees-in-historical-perspective/index.html’

    [       <=>                                                                                          ] 46,429      20.0KB/s   in 2.3s   

2017-07-22 22:18:13 (20.0 KB/s) - ‘activehistory.ca/papers/refugees-in-historical-perspective/index.html’ saved [46429]

--2017-07-22 22:18:15--  http://activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/index.html’

    [       <=>                                                                                          ] 43,621      20.0KB/s   in 2.1s   

2017-07-22 22:18:17 (20.0 KB/s) - ‘activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/index.html’ saved [43621]

--2017-07-22 22:18:19--  http://activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/index.html’

    [        <=>                                                                                         ] 46,286      20.0KB/s   in 2.3s   

2017-07-22 22:18:22 (20.0 KB/s) - ‘activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/index.html’ saved [46286]

--2017-07-22 22:18:24--  http://activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/index.html’

    [            <=>                                                                                     ] 90,187      20.0KB/s   in 4.4s   

2017-07-22 22:18:28 (20.0 KB/s) - ‘activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/index.html’ saved [90187]

--2017-07-22 22:18:30--  http://activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/index.html’

    [           <=>                                                                                      ] 73,347      20.0KB/s   in 3.6s   

2017-07-22 22:18:34 (20.0 KB/s) - ‘activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/index.html’ saved [73347]

--2017-07-22 22:18:36--  http://activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/index.html’

    [            <=>                                                                                     ] 84,683      20.0KB/s   in 4.1s   

2017-07-22 22:18:40 (20.0 KB/s) - ‘activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/index.html’ saved [84683]

--2017-07-22 22:18:42--  http://activehistory.ca/papers/the-social-democracy-question/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/the-social-democracy-question/index.html’

    [           <=>                                                                                      ] 72,505      20.0KB/s   in 3.5s   

2017-07-22 22:18:46 (20.0 KB/s) - ‘activehistory.ca/papers/the-social-democracy-question/index.html’ saved [72505]

--2017-07-22 22:18:48--  http://activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/index.html’

    [             <=>                                                                                    ] 93,741      20.0KB/s   in 4.6s   

2017-07-22 22:18:53 (20.0 KB/s) - ‘activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/index.html’ saved [93741]

--2017-07-22 22:18:55--  http://activehistory.ca/papers/paper-20/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/paper-20/index.html’

    [          <=>                                                                                       ] 71,277      20.0KB/s   in 3.5s   

2017-07-22 22:18:58 (20.0 KB/s) - ‘activehistory.ca/papers/paper-20/index.html’ saved [71277]

--2017-07-22 22:19:00--  http://activehistory.ca/papers/papershistory-papers-19/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/papershistory-papers-19/index.html’

    [                <=>                                                                                 ] 122,806     20.0KB/s   in 6.0s   

2017-07-22 22:19:07 (20.0 KB/s) - ‘activehistory.ca/papers/papershistory-papers-19/index.html’ saved [122806]

--2017-07-22 22:19:09--  http://activehistory.ca/papers/recognizing-the-historical-thinking-project/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/recognizing-the-historical-thinking-project/index.html’

    [        <=>                                                                                         ] 51,913      20.0KB/s   in 2.5s   

2017-07-22 22:19:11 (20.0 KB/s) - ‘activehistory.ca/papers/recognizing-the-historical-thinking-project/index.html’ saved [51913]

--2017-07-22 22:19:13--  http://activehistory.ca/papers/the-royal-proclamation-in-historical-context/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/the-royal-proclamation-in-historical-context/index.html’

    [        <=>                                                                                         ] 55,138      20.0KB/s   in 2.7s   

2017-07-22 22:19:16 (20.0 KB/s) - ‘activehistory.ca/papers/the-royal-proclamation-in-historical-context/index.html’ saved [55138]

--2017-07-22 22:19:18--  http://activehistory.ca/papers/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/?shared=email&msg=fail [following]
--2017-07-22 22:19:20--  http://activehistory.ca/papers/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/index.html?share=email’

    [       <=>                                                                                          ] 53,095      20.6KB/s   in 2.5s   

2017-07-22 22:19:23 (20.6 KB/s) - ‘activehistory.ca/papers/index.html?share=email’ saved [53095]

--2017-07-22 22:19:25--  http://activehistory.ca/papers/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:19:25 ERROR 404: Not Found.

--2017-07-22 22:19:27--  http://activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/index.html’

    [         <=>                                                                                        ] 63,753      20.0KB/s   in 3.1s   

2017-07-22 22:19:31 (20.0 KB/s) - ‘activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/index.html’ saved [63753]

pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:19:33--  http://activehistory.ca/papers/themes/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 905 [application/rss+xml]
activehistory.ca/papers/themes/feed: Not a directoryactivehistory.ca/papers/themes/feed/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/themes/feed/index.html’ (Not a directory).
pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:19:35--  http://activehistory.ca/papers/themes/constitution/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/themes/constitution: Not a directoryactivehistory.ca/papers/themes/constitution/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/themes/constitution/index.html’ (Not a directory).
pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:19:37--  http://activehistory.ca/papers/themes/consumers/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/themes/consumers: Not a directoryactivehistory.ca/papers/themes/consumers/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/themes/consumers/index.html’ (Not a directory).
--2017-07-22 22:19:39--  http://activehistory.ca/papers/themes/education
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/themes/education/ [following]
--2017-07-22 22:19:41--  http://activehistory.ca/papers/themes/education/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/education’

    [       <=>                                                                                          ] 45,708      20.0KB/s   in 2.2s   

2017-07-22 22:19:44 (20.0 KB/s) - ‘activehistory.ca/papers/themes/education’ saved [45708]

--2017-07-22 22:19:46--  http://activehistory.ca/papers/themes/language/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/language/index.html’

    [      <=>                                                                                           ] 43,205      21.8KB/s   in 1.9s   

2017-07-22 22:19:48 (21.8 KB/s) - ‘activehistory.ca/papers/themes/language/index.html’ saved [43205]

--2017-07-22 22:19:50--  http://activehistory.ca/papers/themes/environment/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/environment/index.html’

    [       <=>                                                                                          ] 42,644      20.0KB/s   in 2.1s   

2017-07-22 22:19:52 (20.0 KB/s) - ‘activehistory.ca/papers/themes/environment/index.html’ saved [42644]

--2017-07-22 22:19:54--  http://activehistory.ca/papers/themes/gender-sexuality/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/gender-sexuality/index.html’

    [       <=>                                                                                          ] 43,199      20.0KB/s   in 2.1s   

2017-07-22 22:19:56 (20.0 KB/s) - ‘activehistory.ca/papers/themes/gender-sexuality/index.html’ saved [43199]

--2017-07-22 22:19:58--  http://activehistory.ca/papers/themes/health/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/health/index.html’

    [       <=>                                                                                          ] 44,461      20.0KB/s   in 2.2s   

2017-07-22 22:20:01 (20.0 KB/s) - ‘activehistory.ca/papers/themes/health/index.html’ saved [44461]

--2017-07-22 22:20:03--  http://activehistory.ca/papers/themes/history-in-practice/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/history-in-practice/index.html’

    [       <=>                                                                                          ] 45,175      20.0KB/s   in 2.2s   

2017-07-22 22:20:05 (20.0 KB/s) - ‘activehistory.ca/papers/themes/history-in-practice/index.html’ saved [45175]

--2017-07-22 22:20:07--  http://activehistory.ca/papers/themes/immigration-and-nationality/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/immigration-and-nationality/index.html’

    [       <=>                                                                                          ] 42,951      20.0KB/s   in 2.1s   

2017-07-22 22:20:09 (20.0 KB/s) - ‘activehistory.ca/papers/themes/immigration-and-nationality/index.html’ saved [42951]

--2017-07-22 22:20:11--  http://activehistory.ca/papers/themes/aboriginal/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/aboriginal/index.html’

    [       <=>                                                                                          ] 44,321      20.0KB/s   in 2.2s   

2017-07-22 22:20:14 (20.0 KB/s) - ‘activehistory.ca/papers/themes/aboriginal/index.html’ saved [44321]

--2017-07-22 22:20:16--  http://activehistory.ca/papers/themes/international/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/international/index.html’

    [       <=>                                                                                          ] 43,577      20.0KB/s   in 2.1s   

2017-07-22 22:20:18 (20.0 KB/s) - ‘activehistory.ca/papers/themes/international/index.html’ saved [43577]

--2017-07-22 22:20:20--  http://activehistory.ca/papers/themes/culture/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/culture/index.html’

    [       <=>                                                                                          ] 42,832      20.0KB/s   in 2.1s   

2017-07-22 22:20:22 (20.0 KB/s) - ‘activehistory.ca/papers/themes/culture/index.html’ saved [42832]

--2017-07-22 22:20:24--  http://activehistory.ca/papers/themes/nationalism-and-regionalism/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/nationalism-and-regionalism/index.html’

    [       <=>                                                                                          ] 43,632      20.0KB/s   in 2.1s   

2017-07-22 22:20:26 (20.0 KB/s) - ‘activehistory.ca/papers/themes/nationalism-and-regionalism/index.html’ saved [43632]

--2017-07-22 22:20:28--  http://activehistory.ca/papers/themes/politics-and-parties
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/themes/politics-and-parties/ [following]
--2017-07-22 22:20:31--  http://activehistory.ca/papers/themes/politics-and-parties/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/politics-and-parties’

    [       <=>                                                                                          ] 43,450      20.0KB/s   in 2.1s   

2017-07-22 22:20:33 (20.0 KB/s) - ‘activehistory.ca/papers/themes/politics-and-parties’ saved [43450]

--2017-07-22 22:20:35--  http://activehistory.ca/papers/themes/urban-history-planning-and-local-government/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/urban-history-planning-and-local-government/index.html’

    [       <=>                                                                                          ] 43,153      20.0KB/s   in 2.1s   

2017-07-22 22:20:37 (20.0 KB/s) - ‘activehistory.ca/papers/themes/urban-history-planning-and-local-government/index.html’ saved [43153]

--2017-07-22 22:20:39--  http://activehistory.ca/papers/themes/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/?shared=email&msg=fail [following]
--2017-07-22 22:20:41--  http://activehistory.ca/papers/themes/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/index.html?share=email’

    [       <=>                                                                                          ] 44,357      20.0KB/s   in 2.2s   

2017-07-22 22:20:44 (20.0 KB/s) - ‘activehistory.ca/papers/themes/index.html?share=email’ saved [44357]

--2017-07-22 22:20:46--  http://activehistory.ca/papers/themes/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:20:46 ERROR 404: Not Found.

--2017-07-22 22:20:48--  http://activehistory.ca/papers/indigenous-histories/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 7162 (7.0K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/indigenous-histories/feed/index.html’

100%[===================================================================================================>] 7,162       20.0KB/s   in 0.3s   

2017-07-22 22:20:48 (20.0 KB/s) - ‘activehistory.ca/papers/indigenous-histories/feed/index.html’ saved [7162/7162]

--2017-07-22 22:20:50--  http://activehistory.ca/papers/indigenous-histories/%22http://activehistory.ca/2016/01/a-smudgier-dispossession-is-still-dispossession/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/2016/01/a-smudgier-dispossession-is-still-dispossession/ [following]
--2017-07-22 22:20:52--  http://activehistory.ca/2016/01/a-smudgier-dispossession-is-still-dispossession/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/indigenous-histories/"http:/activehistory.ca/2016/01/a-smudgier-dispossession-is-still-dispossession/index.html’

    [         <=>                                                                                        ] 61,839      20.0KB/s   in 3.0s   

2017-07-22 22:20:56 (20.0 KB/s) - ‘activehistory.ca/papers/indigenous-histories/"http:/activehistory.ca/2016/01/a-smudgier-dispossession-is-still-dispossession/index.html’ saved [61839]

--2017-07-22 22:20:58--  http://activehistory.ca/papers/indigenous-histories/%22http://activehistory.ca/2016/01/political-depression-in-a-time-of-reconciliation/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/2016/01/political-depression-in-a-time-of-reconciliation/ [following]
--2017-07-22 22:21:00--  http://activehistory.ca/2016/01/political-depression-in-a-time-of-reconciliation/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/indigenous-histories/"http:/activehistory.ca/2016/01/political-depression-in-a-time-of-reconciliation/index.html’

    [         <=>                                                                                        ] 61,936      20.0KB/s   in 3.0s   

2017-07-22 22:21:03 (20.0 KB/s) - ‘activehistory.ca/papers/indigenous-histories/"http:/activehistory.ca/2016/01/political-depression-in-a-time-of-reconciliation/index.html’ saved [61936]

--2017-07-22 22:21:05--  http://activehistory.ca/papers/indigenous-histories/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/indigenous-histories/?shared=email&msg=fail [following]
--2017-07-22 22:21:07--  http://activehistory.ca/papers/indigenous-histories/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/indigenous-histories/index.html?share=email’

    [       <=>                                                                                          ] 48,877      20.0KB/s   in 2.4s   

2017-07-22 22:21:10 (20.0 KB/s) - ‘activehistory.ca/papers/indigenous-histories/index.html?share=email’ saved [48877]

--2017-07-22 22:21:12--  http://activehistory.ca/papers/indigenous-histories/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:21:12 ERROR 404: Not Found.

--2017-07-22 22:21:14--  http://activehistory.ca/papers/refugees-in-historical-perspective/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 961 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/refugees-in-historical-perspective/feed/index.html’

100%[===================================================================================================>] 961         --.-K/s   in 0s      

2017-07-22 22:21:14 (81.1 MB/s) - ‘activehistory.ca/papers/refugees-in-historical-perspective/feed/index.html’ saved [961/961]

--2017-07-22 22:21:16--  http://activehistory.ca/papers/refugees-in-historical-perspective/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/refugees-in-historical-perspective/?shared=email&msg=fail [following]
--2017-07-22 22:21:18--  http://activehistory.ca/papers/refugees-in-historical-perspective/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/refugees-in-historical-perspective/index.html?share=email’

    [        <=>                                                                                         ] 46,599      20.0KB/s   in 2.3s   

2017-07-22 22:21:21 (20.0 KB/s) - ‘activehistory.ca/papers/refugees-in-historical-perspective/index.html?share=email’ saved [46599]

--2017-07-22 22:21:23--  http://activehistory.ca/papers/refugees-in-historical-perspective/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:21:23 ERROR 404: Not Found.

--2017-07-22 22:21:25--  http://activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 985 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/feed/index.html’

100%[===================================================================================================>] 985         --.-K/s   in 0s      

2017-07-22 22:21:25 (71.1 MB/s) - ‘activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/feed/index.html’ saved [985/985]

--2017-07-22 22:21:27--  http://activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/?shared=email&msg=fail [following]
--2017-07-22 22:21:29--  http://activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/index.html?share=email’

    [       <=>                                                                                          ] 43,791      20.0KB/s   in 2.1s   

2017-07-22 22:21:31 (20.0 KB/s) - ‘activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/index.html?share=email’ saved [43791]

--2017-07-22 22:21:33--  http://activehistory.ca/papers/commemorating-35-years-of-the-marathon-of-hope/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:21:34 ERROR 404: Not Found.

--2017-07-22 22:21:36--  http://activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 1029 (1.0K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/feed/index.html’

100%[===================================================================================================>] 1,029       --.-K/s   in 0s      

2017-07-22 22:21:36 (87.1 MB/s) - ‘activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/feed/index.html’ saved [1029/1029]

--2017-07-22 22:21:38--  http://activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/?shared=email&msg=fail [following]
--2017-07-22 22:21:40--  http://activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/index.html?share=email’

    [        <=>                                                                                         ] 46,456      20.0KB/s   in 2.3s   

2017-07-22 22:21:42 (20.0 KB/s) - ‘activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/index.html?share=email’ saved [46456]

--2017-07-22 22:21:44--  http://activehistory.ca/papers/theme-week-infectious-disease-contagion-and-the-history-of-vaccines/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:21:44 ERROR 404: Not Found.

--2017-07-22 22:21:46--  http://activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 5944 (5.8K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/feed/index.html’

100%[===================================================================================================>] 5,944       20.0KB/s   in 0.3s   

2017-07-22 22:21:47 (20.0 KB/s) - ‘activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/feed/index.html’ saved [5944/5944]

--2017-07-22 22:21:49--  http://activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/?shared=email&msg=fail [following]
--2017-07-22 22:21:51--  http://activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/index.html?share=email’

    [            <=>                                                                                     ] 90,357      20.0KB/s   in 4.4s   

2017-07-22 22:21:56 (20.0 KB/s) - ‘activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/index.html?share=email’ saved [90357]

--2017-07-22 22:21:58--  http://activehistory.ca/papers/truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:21:58 ERROR 404: Not Found.

--2017-07-22 22:22:00--  http://activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 3898 (3.8K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/feed/index.html’

100%[===================================================================================================>] 3,898       --.-K/s   in 0s      

2017-07-22 22:22:00 (501 MB/s) - ‘activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/feed/index.html’ saved [3898/3898]

--2017-07-22 22:22:02--  http://activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/?shared=email&msg=fail [following]
--2017-07-22 22:22:04--  http://activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/index.html?share=email’

    [           <=>                                                                                      ] 73,517      20.0KB/s   in 3.6s   

2017-07-22 22:22:08 (20.0 KB/s) - ‘activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/index.html?share=email’ saved [73517]

--2017-07-22 22:22:10--  http://activehistory.ca/papers/the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:22:10 ERROR 404: Not Found.

--2017-07-22 22:22:12--  http://activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 3975 (3.9K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/feed/index.html’

100%[===================================================================================================>] 3,975       --.-K/s   in 0s      

2017-07-22 22:22:12 (260 MB/s) - ‘activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/feed/index.html’ saved [3975/3975]

--2017-07-22 22:22:14--  http://activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/%E2%80%9C
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/2009/12/%e2%80%9ccopenhagen-is-pm%e2%80%99s-big-chance%e2%80%9d-history-phd-candidates-argue/ [following]
--2017-07-22 22:22:16--  http://activehistory.ca/2009/12/%e2%80%9ccopenhagen-is-pm%e2%80%99s-big-chance%e2%80%9d-history-phd-candidates-argue/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/\342%80%9C’

    [      <=>                                                                                           ] 46,495      20.8KB/s   in 2.2s   

2017-07-22 22:22:19 (20.8 KB/s) - ‘activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/\342%80%9C’ saved [46495]

--2017-07-22 22:22:21--  http://activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/?shared=email&msg=fail [following]
--2017-07-22 22:22:23--  http://activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/index.html?share=email’

    [            <=>                                                                                     ] 84,853      20.0KB/s   in 4.1s   

2017-07-22 22:22:27 (20.0 KB/s) - ‘activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/index.html?share=email’ saved [84853]

--2017-07-22 22:22:29--  http://activehistory.ca/papers/disappearing-into-white-space-indigenous-toronto-1900-1914/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:22:29 ERROR 404: Not Found.

--2017-07-22 22:22:31--  http://activehistory.ca/papers/the-social-democracy-question/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 4043 (3.9K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/the-social-democracy-question/feed/index.html’

100%[===================================================================================================>] 4,043       --.-K/s   in 0s      

2017-07-22 22:22:31 (357 MB/s) - ‘activehistory.ca/papers/the-social-democracy-question/feed/index.html’ saved [4043/4043]

--2017-07-22 22:22:33--  http://activehistory.ca/papers/the-social-democracy-question/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/the-social-democracy-question/?shared=email&msg=fail [following]
--2017-07-22 22:22:36--  http://activehistory.ca/papers/the-social-democracy-question/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/the-social-democracy-question/index.html?share=email’

    [           <=>                                                                                      ] 72,675      20.0KB/s   in 3.5s   

2017-07-22 22:22:39 (20.0 KB/s) - ‘activehistory.ca/papers/the-social-democracy-question/index.html?share=email’ saved [72675]

--2017-07-22 22:22:41--  http://activehistory.ca/papers/the-social-democracy-question/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:22:42 ERROR 404: Not Found.

--2017-07-22 22:22:44--  http://activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 4235 (4.1K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/feed/index.html’

100%[===================================================================================================>] 4,235       20.0KB/s   in 0.2s   

2017-07-22 22:22:44 (20.0 KB/s) - ‘activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/feed/index.html’ saved [4235/4235]

--2017-07-22 22:22:46--  http://activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/?shared=email&msg=fail [following]
--2017-07-22 22:22:48--  http://activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/index.html?share=email’

    [             <=>                                                                                    ] 93,911      20.0KB/s   in 4.6s   

2017-07-22 22:22:53 (20.0 KB/s) - ‘activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/index.html?share=email’ saved [93911]

--2017-07-22 22:22:55--  http://activehistory.ca/papers/bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:22:55 ERROR 404: Not Found.

--2017-07-22 22:22:57--  http://activehistory.ca/papers/paper-20/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [application/rss+xml]
Saving to: ‘activehistory.ca/papers/paper-20/feed/index.html’

    [  <=>                                                                                               ] 8,540       20.8KB/s   in 0.4s   

2017-07-22 22:22:58 (20.8 KB/s) - ‘activehistory.ca/papers/paper-20/feed/index.html’ saved [8540]

--2017-07-22 22:23:00--  http://activehistory.ca/papers/paper-20/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/paper-20/?shared=email&msg=fail [following]
--2017-07-22 22:23:02--  http://activehistory.ca/papers/paper-20/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/paper-20/index.html?share=email’

    [          <=>                                                                                       ] 71,447      20.0KB/s   in 3.5s   

2017-07-22 22:23:06 (20.0 KB/s) - ‘activehistory.ca/papers/paper-20/index.html?share=email’ saved [71447]

--2017-07-22 22:23:08--  http://activehistory.ca/papers/paper-20/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:23:08 ERROR 404: Not Found.

--2017-07-22 22:23:10--  http://activehistory.ca/papers/papershistory-papers-19/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 6851 (6.7K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/papershistory-papers-19/feed/index.html’

100%[===================================================================================================>] 6,851       20.0KB/s   in 0.3s   

2017-07-22 22:23:10 (20.0 KB/s) - ‘activehistory.ca/papers/papershistory-papers-19/feed/index.html’ saved [6851/6851]

--2017-07-22 22:23:12--  http://activehistory.ca/papers/papershistory-papers-19/Figure%20Four
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:23:12 ERROR 404: Not Found.

--2017-07-22 22:23:14--  http://activehistory.ca/papers/papershistory-papers-19/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/papershistory-papers-19/?shared=email&msg=fail [following]
--2017-07-22 22:23:17--  http://activehistory.ca/papers/papershistory-papers-19/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/papershistory-papers-19/index.html?share=email’

    [                <=>                                                                                 ] 122,976     20.0KB/s   in 6.0s   

2017-07-22 22:23:23 (20.0 KB/s) - ‘activehistory.ca/papers/papershistory-papers-19/index.html?share=email’ saved [122976]

--2017-07-22 22:23:25--  http://activehistory.ca/papers/papershistory-papers-19/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:23:25 ERROR 404: Not Found.

--2017-07-22 22:23:27--  http://activehistory.ca/papers/recognizing-the-historical-thinking-project/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [application/rss+xml]
Saving to: ‘activehistory.ca/papers/recognizing-the-historical-thinking-project/feed/index.html’

    [  <=>                                                                                               ] 11,185      27.3KB/s   in 0.4s   

2017-07-22 22:23:28 (27.3 KB/s) - ‘activehistory.ca/papers/recognizing-the-historical-thinking-project/feed/index.html’ saved [11185]

--2017-07-22 22:23:30--  http://activehistory.ca/papers/recognizing-the-historical-thinking-project/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/recognizing-the-historical-thinking-project/?shared=email&msg=fail [following]
--2017-07-22 22:23:32--  http://activehistory.ca/papers/recognizing-the-historical-thinking-project/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/recognizing-the-historical-thinking-project/index.html?share=email’

    [        <=>                                                                                         ] 52,083      20.0KB/s   in 2.5s   

2017-07-22 22:23:34 (20.0 KB/s) - ‘activehistory.ca/papers/recognizing-the-historical-thinking-project/index.html?share=email’ saved [52083]

--2017-07-22 22:23:36--  http://activehistory.ca/papers/recognizing-the-historical-thinking-project/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:23:37 ERROR 404: Not Found.

--2017-07-22 22:23:39--  http://activehistory.ca/papers/the-royal-proclamation-in-historical-context/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [application/rss+xml]
Saving to: ‘activehistory.ca/papers/the-royal-proclamation-in-historical-context/feed/index.html’

    [   <=>                                                                                              ] 12,878      20.0KB/s   in 0.6s   

2017-07-22 22:23:39 (20.0 KB/s) - ‘activehistory.ca/papers/the-royal-proclamation-in-historical-context/feed/index.html’ saved [12878]

--2017-07-22 22:23:41--  http://activehistory.ca/papers/the-royal-proclamation-in-historical-context/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/the-royal-proclamation-in-historical-context/?shared=email&msg=fail [following]
--2017-07-22 22:23:44--  http://activehistory.ca/papers/the-royal-proclamation-in-historical-context/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/the-royal-proclamation-in-historical-context/index.html?share=email’

    [        <=>                                                                                         ] 55,308      20.0KB/s   in 2.7s   

2017-07-22 22:23:46 (20.0 KB/s) - ‘activehistory.ca/papers/the-royal-proclamation-in-historical-context/index.html?share=email’ saved [55308]

--2017-07-22 22:23:48--  http://activehistory.ca/papers/the-royal-proclamation-in-historical-context/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:23:49 ERROR 404: Not Found.

--2017-07-22 22:23:51--  http://activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [application/rss+xml]
Saving to: ‘activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/feed/index.html’

    [  <=>                                                                                               ] 11,251      27.4KB/s   in 0.4s   

2017-07-22 22:23:51 (27.4 KB/s) - ‘activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/feed/index.html’ saved [11251]

--2017-07-22 22:23:53--  http://activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/?shared=email&msg=fail [following]
--2017-07-22 22:23:55--  http://activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/index.html?share=email’

    [         <=>                                                                                        ] 63,923      20.0KB/s   in 3.1s   

2017-07-22 22:23:59 (20.0 KB/s) - ‘activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/index.html?share=email’ saved [63923]

--2017-07-22 22:24:01--  http://activehistory.ca/papers/canadas-first-world-war-a-centennial-series-on-activehistory-ca/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:24:01 ERROR 404: Not Found.

pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:24:03--  http://activehistory.ca/papers/themes/education/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 1556 (1.5K) [application/rss+xml]
activehistory.ca/papers/themes/education/feed: Not a directoryactivehistory.ca/papers/themes/education/feed/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/themes/education/feed/index.html’ (Not a directory).
--2017-07-22 22:24:05--  http://activehistory.ca/papers/history-papers-15/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-15/index.html’

    [            <=>                                                                                     ] 85,863      20.0KB/s   in 4.2s   

2017-07-22 22:24:09 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-15/index.html’ saved [85863]

--2017-07-22 22:24:11--  http://activehistory.ca/papers/history-papers-11
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/history-papers-11/ [following]
--2017-07-22 22:24:14--  http://activehistory.ca/papers/history-papers-11/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-11’

    [            <=>                                                                                     ] 81,856      20.0KB/s   in 4.0s   

2017-07-22 22:24:18 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-11’ saved [81856]

--2017-07-22 22:24:20--  http://activehistory.ca/papers/history-paper-5/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-5/index.html’

    [              <=>                                                                                   ] 105,391     20.0KB/s   in 5.1s   

2017-07-22 22:24:25 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-5/index.html’ saved [105391]

pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:24:27--  http://activehistory.ca/papers/themes/education/.http://activehistory.ca/papers/historypaper-8/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/historypaper-8/ [following]
pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:24:29--  http://activehistory.ca/papers/historypaper-8/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/themes/education/.http:/activehistory.ca/papers/historypaper-8: Not a directoryactivehistory.ca/papers/themes/education/.http:/activehistory.ca/papers/historypaper-8/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/themes/education/.http:/activehistory.ca/papers/historypaper-8/index.html’ (Not a directory).
--2017-07-22 22:24:31--  http://activehistory.ca/papers/themes/papers/what-can-oral-history-teach-us/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/what-can-oral-history-teach-us/ [following]
--2017-07-22 22:24:34--  http://activehistory.ca/papers/what-can-oral-history-teach-us/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/papers/what-can-oral-history-teach-us/index.html’

    [               <=>                                                                                  ] 109,019     20.0KB/s   in 5.3s   

2017-07-22 22:24:39 (20.0 KB/s) - ‘activehistory.ca/papers/themes/papers/what-can-oral-history-teach-us/index.html’ saved [109019]

--2017-07-22 22:24:41--  http://activehistory.ca/papers/history-papers-13/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-13/index.html’

    [          <=>                                                                                       ] 69,092      20.0KB/s   in 3.4s   

2017-07-22 22:24:45 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-13/index.html’ saved [69092]

--2017-07-22 22:24:47--  http://activehistory.ca/papers/themes/education/?share=email
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/education/?shared=email&msg=fail [following]
--2017-07-22 22:24:49--  http://activehistory.ca/papers/themes/education/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/education/index.html?share=email’

    [       <=>                                                                                          ] 45,878      20.0KB/s   in 2.2s   

2017-07-22 22:24:51 (20.0 KB/s) - ‘activehistory.ca/papers/themes/education/index.html?share=email’ saved [45878]

--2017-07-22 22:24:53--  http://activehistory.ca/papers/themes/education/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:24:53 ERROR 404: Not Found.

--2017-07-22 22:24:55--  http://activehistory.ca/papers/themes/language/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 939 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/language/feed/index.html’

100%[===================================================================================================>] 939         --.-K/s   in 0s      

2017-07-22 22:24:55 (86.6 MB/s) - ‘activehistory.ca/papers/themes/language/feed/index.html’ saved [939/939]

--2017-07-22 22:24:57--  http://activehistory.ca/papers/papershistory-papers-17/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/papershistory-papers-17/index.html’

    [          <=>                                                                                       ] 70,277      20.0KB/s   in 3.4s   

2017-07-22 22:25:01 (20.0 KB/s) - ‘activehistory.ca/papers/papershistory-papers-17/index.html’ saved [70277]

--2017-07-22 22:25:03--  http://activehistory.ca/papers/themes/papers/historypaper-9/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/historypaper-9/ [following]
--2017-07-22 22:25:05--  http://activehistory.ca/papers/historypaper-9/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/papers/historypaper-9/index.html’

    [         <=>                                                                                        ] 59,778      20.0KB/s   in 2.9s   

2017-07-22 22:25:08 (20.0 KB/s) - ‘activehistory.ca/papers/themes/papers/historypaper-9/index.html’ saved [59778]

--2017-07-22 22:25:10--  http://activehistory.ca/papers/themes/language/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/language/?shared=email&msg=fail [following]
--2017-07-22 22:25:13--  http://activehistory.ca/papers/themes/language/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/language/index.html?share=email’

    [       <=>                                                                                          ] 43,375      20.0KB/s   in 2.1s   

2017-07-22 22:25:15 (20.0 KB/s) - ‘activehistory.ca/papers/themes/language/index.html?share=email’ saved [43375]

--2017-07-22 22:25:17--  http://activehistory.ca/papers/themes/language/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:25:17 ERROR 404: Not Found.

--2017-07-22 22:25:19--  http://activehistory.ca/papers/themes/environment/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 945 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/environment/feed/index.html’

100%[===================================================================================================>] 945         --.-K/s   in 0s      

2017-07-22 22:25:19 (107 MB/s) - ‘activehistory.ca/papers/themes/environment/feed/index.html’ saved [945/945]

--2017-07-22 22:25:21--  http://activehistory.ca/papers/themes/papers/history-paper-6/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/history-paper-6/ [following]
--2017-07-22 22:25:23--  http://activehistory.ca/papers/history-paper-6/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/papers/history-paper-6/index.html’

    [           <=>                                                                                      ] 74,186      20.0KB/s   in 3.6s   

2017-07-22 22:25:27 (20.0 KB/s) - ‘activehistory.ca/papers/themes/papers/history-paper-6/index.html’ saved [74186]

--2017-07-22 22:25:29--  http://activehistory.ca/papers/themes/environment/?share=email
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/environment/?shared=email&msg=fail [following]
--2017-07-22 22:25:31--  http://activehistory.ca/papers/themes/environment/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/environment/index.html?share=email’

    [       <=>                                                                                          ] 42,814      20.0KB/s   in 2.1s   

2017-07-22 22:25:33 (20.0 KB/s) - ‘activehistory.ca/papers/themes/environment/index.html?share=email’ saved [42814]

--2017-07-22 22:25:35--  http://activehistory.ca/papers/themes/environment/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:25:36 ERROR 404: Not Found.

--2017-07-22 22:25:38--  http://activehistory.ca/papers/themes/gender-sexuality/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 936 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/gender-sexuality/feed/index.html’

100%[===================================================================================================>] 936         --.-K/s   in 0s      

2017-07-22 22:25:38 (67.8 MB/s) - ‘activehistory.ca/papers/themes/gender-sexuality/feed/index.html’ saved [936/936]

--2017-07-22 22:25:40--  http://activehistory.ca/papers/history-papers-14/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-14/index.html’

    [            <=>                                                                                     ] 89,915      20.0KB/s   in 4.4s   

2017-07-22 22:25:44 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-14/index.html’ saved [89915]

--2017-07-22 22:25:46--  http://activehistory.ca/papers/themes/gender-sexuality/?share=email
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/gender-sexuality/?shared=email&msg=fail [following]
--2017-07-22 22:25:49--  http://activehistory.ca/papers/themes/gender-sexuality/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/gender-sexuality/index.html?share=email’

    [       <=>                                                                                          ] 43,369      20.0KB/s   in 2.1s   

2017-07-22 22:25:51 (20.0 KB/s) - ‘activehistory.ca/papers/themes/gender-sexuality/index.html?share=email’ saved [43369]

--2017-07-22 22:25:53--  http://activehistory.ca/papers/themes/gender-sexuality/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:25:53 ERROR 404: Not Found.

--2017-07-22 22:25:55--  http://activehistory.ca/papers/themes/health/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 945 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/health/feed/index.html’

100%[===================================================================================================>] 945         --.-K/s   in 0s      

2017-07-22 22:25:55 (109 MB/s) - ‘activehistory.ca/papers/themes/health/feed/index.html’ saved [945/945]

--2017-07-22 22:25:57--  http://activehistory.ca/papers/history-papers-16/%20
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/history-papers-16/ [following]
--2017-07-22 22:25:59--  http://activehistory.ca/papers/history-papers-16/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-16/ ’

    [           <=>                                                                                      ] 74,466      20.0KB/s   in 3.6s   

2017-07-22 22:26:03 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-16/ ’ saved [74466]

--2017-07-22 22:26:05--  http://activehistory.ca/papers/historypaper-10/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/historypaper-10/index.html’

    [                <=>                                                                                 ] 117,623     20.0KB/s   in 5.7s   

2017-07-22 22:26:11 (20.0 KB/s) - ‘activehistory.ca/papers/historypaper-10/index.html’ saved [117623]

--2017-07-22 22:26:13--  http://activehistory.ca/papers/themes/health/The%20Canadian%20Centre%20for%20Bioethical%20Reform%20Campus%20Genocide%20Awareness%20Project%20as%20Propaganda%20for%20Fetal%20Rights
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:26:13 ERROR 404: Not Found.

--2017-07-22 22:26:15--  http://activehistory.ca/papers/themes/health/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/health/?shared=email&msg=fail [following]
--2017-07-22 22:26:17--  http://activehistory.ca/papers/themes/health/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/health/index.html?share=email’

    [       <=>                                                                                          ] 44,631      20.0KB/s   in 2.2s   

2017-07-22 22:26:20 (20.0 KB/s) - ‘activehistory.ca/papers/themes/health/index.html?share=email’ saved [44631]

--2017-07-22 22:26:22--  http://activehistory.ca/papers/themes/health/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:26:22 ERROR 404: Not Found.

--2017-07-22 22:26:24--  http://activehistory.ca/papers/themes/history-in-practice/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 938 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/history-in-practice/feed/index.html’

100%[===================================================================================================>] 938         --.-K/s   in 0s      

2017-07-22 22:26:24 (73.8 MB/s) - ‘activehistory.ca/papers/themes/history-in-practice/feed/index.html’ saved [938/938]

--2017-07-22 22:26:26--  http://activehistory.ca/papers/themes/papers/roundtable/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/roundtable/ [following]
--2017-07-22 22:26:28--  http://activehistory.ca/papers/roundtable/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/papers/roundtable/index.html’

    [          <=>                                                                                       ] 63,531      20.0KB/s   in 3.1s   

2017-07-22 22:26:32 (20.0 KB/s) - ‘activehistory.ca/papers/themes/papers/roundtable/index.html’ saved [63531]

--2017-07-22 22:26:34--  http://activehistory.ca/papers/the-home-archivist/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/the-home-archivist/index.html’

    [      <=>                                                                                           ] 43,471      21.3KB/s   in 2.0s   

2017-07-22 22:26:36 (21.3 KB/s) - ‘activehistory.ca/papers/the-home-archivist/index.html’ saved [43471]

--2017-07-22 22:26:38--  http://activehistory.ca/papers/themes/history-in-practice/.http://activehistory.ca/papers/historypaper-8/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/historypaper-8/ [following]
--2017-07-22 22:26:40--  http://activehistory.ca/papers/historypaper-8/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/history-in-practice/.http:/activehistory.ca/papers/historypaper-8/index.html’

    [           <=>                                                                                      ] 74,878      20.0KB/s   in 3.7s   

2017-07-22 22:26:44 (20.0 KB/s) - ‘activehistory.ca/papers/themes/history-in-practice/.http:/activehistory.ca/papers/historypaper-8/index.html’ saved [74878]

--2017-07-22 22:26:46--  http://activehistory.ca/papers/themes/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/ [following]
--2017-07-22 22:26:48--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/index.html’

    [          <=>                                                                                       ] 75,713      20.0KB/s   in 3.7s   

2017-07-22 22:26:52 (20.0 KB/s) - ‘activehistory.ca/papers/themes/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/index.html’ saved [75713]

--2017-07-22 22:26:54--  http://activehistory.ca/papers/themes/history-in-practice/?share=email
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/history-in-practice/?shared=email&msg=fail [following]
--2017-07-22 22:26:56--  http://activehistory.ca/papers/themes/history-in-practice/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/history-in-practice/index.html?share=email’

    [       <=>                                                                                          ] 45,345      20.0KB/s   in 2.2s   

2017-07-22 22:26:58 (20.0 KB/s) - ‘activehistory.ca/papers/themes/history-in-practice/index.html?share=email’ saved [45345]

--2017-07-22 22:27:00--  http://activehistory.ca/papers/themes/history-in-practice/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:27:00 ERROR 404: Not Found.

--2017-07-22 22:27:02--  http://activehistory.ca/papers/themes/immigration-and-nationality/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 954 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/immigration-and-nationality/feed/index.html’

100%[===================================================================================================>] 954         --.-K/s   in 0s      

2017-07-22 22:27:03 (78.1 MB/s) - ‘activehistory.ca/papers/themes/immigration-and-nationality/feed/index.html’ saved [954/954]

--2017-07-22 22:27:05--  http://activehistory.ca/papers/history-papers-12/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-12/index.html’

    [             <=>                                                                                    ] 108,203     20.0KB/s   in 5.3s   

2017-07-22 22:27:10 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-12/index.html’ saved [108203]

--2017-07-22 22:27:12--  http://activehistory.ca/papers/themes/immigration-and-nationality/?share=email
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/immigration-and-nationality/?shared=email&msg=fail [following]
--2017-07-22 22:27:14--  http://activehistory.ca/papers/themes/immigration-and-nationality/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/immigration-and-nationality/index.html?share=email’

    [       <=>                                                                                          ] 43,121      20.0KB/s   in 2.1s   

2017-07-22 22:27:17 (20.0 KB/s) - ‘activehistory.ca/papers/themes/immigration-and-nationality/index.html?share=email’ saved [43121]

--2017-07-22 22:27:19--  http://activehistory.ca/papers/themes/immigration-and-nationality/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:27:19 ERROR 404: Not Found.

--2017-07-22 22:27:21--  http://activehistory.ca/papers/themes/aboriginal/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 930 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/aboriginal/feed/index.html’

100%[===================================================================================================>] 930         --.-K/s   in 0s      

2017-07-22 22:27:21 (35.5 MB/s) - ‘activehistory.ca/papers/themes/aboriginal/feed/index.html’ saved [930/930]

--2017-07-22 22:27:23--  http://activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/index.html’

    [       <=>                                                                                          ] 44,021      20.0KB/s   in 2.1s   

2017-07-22 22:27:25 (20.0 KB/s) - ‘activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/index.html’ saved [44021]

--2017-07-22 22:27:27--  http://activehistory.ca/papers/themes/aboriginal/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/aboriginal/?shared=email&msg=fail [following]
--2017-07-22 22:27:29--  http://activehistory.ca/papers/themes/aboriginal/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/aboriginal/index.html?share=email’

    [       <=>                                                                                          ] 44,491      20.0KB/s   in 2.2s   

2017-07-22 22:27:32 (20.0 KB/s) - ‘activehistory.ca/papers/themes/aboriginal/index.html?share=email’ saved [44491]

--2017-07-22 22:27:34--  http://activehistory.ca/papers/themes/aboriginal/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:27:34 ERROR 404: Not Found.

--2017-07-22 22:27:36--  http://activehistory.ca/papers/themes/international/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 947 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/international/feed/index.html’

100%[===================================================================================================>] 947         --.-K/s   in 0s      

2017-07-22 22:27:36 (112 MB/s) - ‘activehistory.ca/papers/themes/international/feed/index.html’ saved [947/947]

--2017-07-22 22:27:38--  http://activehistory.ca/papers/history-paper-2
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/history-paper-2/ [following]
--2017-07-22 22:27:40--  http://activehistory.ca/papers/history-paper-2/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-2’

    [           <=>                                                                                      ] 80,752      20.0KB/s   in 3.9s   

2017-07-22 22:27:44 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-2’ saved [80752]

--2017-07-22 22:27:46--  http://activehistory.ca/papers/history-paper-1/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-1/index.html’

    [          <=>                                                                                       ] 70,745      20.0KB/s   in 3.5s   

2017-07-22 22:27:50 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-1/index.html’ saved [70745]

--2017-07-22 22:27:52--  http://activehistory.ca/papers/themes/papers/history-paper-4/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/history-paper-4/ [following]
--2017-07-22 22:27:54--  http://activehistory.ca/papers/history-paper-4/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/papers/history-paper-4/index.html’

    [          <=>                                                                                       ] 66,676      20.0KB/s   in 3.3s   

2017-07-22 22:27:58 (20.0 KB/s) - ‘activehistory.ca/papers/themes/papers/history-paper-4/index.html’ saved [66676]

--2017-07-22 22:28:00--  http://activehistory.ca/papers/themes/papers/themes/international/vietnam-et-cuba
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/themes/international/vietnam-et-cuba/ [following]
--2017-07-22 22:28:02--  http://activehistory.ca/papers/themes/international/vietnam-et-cuba/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/papers/themes/international/vietnam-et-cuba’

    [          <=>                                                                                       ] 66,185      20.0KB/s   in 3.2s   

2017-07-22 22:28:05 (20.0 KB/s) - ‘activehistory.ca/papers/themes/papers/themes/international/vietnam-et-cuba’ saved [66185]

--2017-07-22 22:28:07--  http://activehistory.ca/papers/history-paper-3
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/history-paper-3/ [following]
--2017-07-22 22:28:09--  http://activehistory.ca/papers/history-paper-3/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-3’

    [             <=>                                                                                    ] 93,943      20.0KB/s   in 4.6s   

2017-07-22 22:28:14 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-3’ saved [93943]

--2017-07-22 22:28:16--  http://activehistory.ca/papers/themes/international/?share=email
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/international/?shared=email&msg=fail [following]
--2017-07-22 22:28:18--  http://activehistory.ca/papers/themes/international/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/international/index.html?share=email’

    [       <=>                                                                                          ] 43,747      20.0KB/s   in 2.1s   

2017-07-22 22:28:21 (20.0 KB/s) - ‘activehistory.ca/papers/themes/international/index.html?share=email’ saved [43747]

--2017-07-22 22:28:23--  http://activehistory.ca/papers/themes/international/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:28:23 ERROR 404: Not Found.

--2017-07-22 22:28:25--  http://activehistory.ca/papers/themes/culture/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 924 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/culture/feed/index.html’

100%[===================================================================================================>] 924         --.-K/s   in 0s      

2017-07-22 22:28:25 (71.1 MB/s) - ‘activehistory.ca/papers/themes/culture/feed/index.html’ saved [924/924]

--2017-07-22 22:28:27--  http://activehistory.ca/papers/themes/culture/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/culture/?shared=email&msg=fail [following]
--2017-07-22 22:28:29--  http://activehistory.ca/papers/themes/culture/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/culture/index.html?share=email’

    [       <=>                                                                                          ] 43,002      20.0KB/s   in 2.1s   

2017-07-22 22:28:32 (20.0 KB/s) - ‘activehistory.ca/papers/themes/culture/index.html?share=email’ saved [43002]

--2017-07-22 22:28:34--  http://activehistory.ca/papers/themes/culture/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:28:34 ERROR 404: Not Found.

--2017-07-22 22:28:36--  http://activehistory.ca/papers/themes/nationalism-and-regionalism/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 954 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/nationalism-and-regionalism/feed/index.html’

100%[===================================================================================================>] 954         --.-K/s   in 0s      

2017-07-22 22:28:36 (79.6 MB/s) - ‘activehistory.ca/papers/themes/nationalism-and-regionalism/feed/index.html’ saved [954/954]

--2017-07-22 22:28:38--  http://activehistory.ca/papers/themes/nationalism-and-regionalism/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/nationalism-and-regionalism/?shared=email&msg=fail [following]
--2017-07-22 22:28:40--  http://activehistory.ca/papers/themes/nationalism-and-regionalism/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/nationalism-and-regionalism/index.html?share=email’

    [       <=>                                                                                          ] 43,802      20.0KB/s   in 2.1s   

2017-07-22 22:28:43 (20.0 KB/s) - ‘activehistory.ca/papers/themes/nationalism-and-regionalism/index.html?share=email’ saved [43802]

--2017-07-22 22:28:45--  http://activehistory.ca/papers/themes/nationalism-and-regionalism/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:28:45 ERROR 404: Not Found.

pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:28:47--  http://activehistory.ca/papers/themes/politics-and-parties/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 940 [application/rss+xml]
activehistory.ca/papers/themes/politics-and-parties/feed: Not a directoryactivehistory.ca/papers/themes/politics-and-parties/feed/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/themes/politics-and-parties/feed/index.html’ (Not a directory).
--2017-07-22 22:28:49--  http://activehistory.ca/papers/200-years-of-the-old-chieftain/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/200-years-of-the-old-chieftain/index.html’

    [       <=>                                                                                          ] 43,815      20.0KB/s   in 2.1s   

2017-07-22 22:28:51 (20.0 KB/s) - ‘activehistory.ca/papers/200-years-of-the-old-chieftain/index.html’ saved [43815]

--2017-07-22 22:28:53--  http://activehistory.ca/papers/themes/politics-and-parties/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/politics-and-parties/?shared=email&msg=fail [following]
--2017-07-22 22:28:55--  http://activehistory.ca/papers/themes/politics-and-parties/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/politics-and-parties/index.html?share=email’

    [       <=>                                                                                          ] 43,620      20.0KB/s   in 2.1s   

2017-07-22 22:28:58 (20.0 KB/s) - ‘activehistory.ca/papers/themes/politics-and-parties/index.html?share=email’ saved [43620]

--2017-07-22 22:29:00--  http://activehistory.ca/papers/themes/politics-and-parties/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:29:00 ERROR 404: Not Found.

--2017-07-22 22:29:02--  http://activehistory.ca/papers/themes/urban-history-planning-and-local-government/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 987 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/urban-history-planning-and-local-government/feed/index.html’

100%[===================================================================================================>] 987         --.-K/s   in 0s      

2017-07-22 22:29:02 (126 MB/s) - ‘activehistory.ca/papers/themes/urban-history-planning-and-local-government/feed/index.html’ saved [987/987]

--2017-07-22 22:29:04--  http://activehistory.ca/papers/themes/urban-history-planning-and-local-government/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/urban-history-planning-and-local-government/?shared=email&msg=fail [following]
--2017-07-22 22:29:06--  http://activehistory.ca/papers/themes/urban-history-planning-and-local-government/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/urban-history-planning-and-local-government/index.html?share=email’

    [       <=>                                                                                          ] 43,323      20.0KB/s   in 2.1s   

2017-07-22 22:29:09 (20.0 KB/s) - ‘activehistory.ca/papers/themes/urban-history-planning-and-local-government/index.html?share=email’ saved [43323]

--2017-07-22 22:29:11--  http://activehistory.ca/papers/themes/urban-history-planning-and-local-government/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:29:11 ERROR 404: Not Found.

--2017-07-22 22:29:13--  http://activehistory.ca/papers/history-papers-15/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 6579 (6.4K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/history-papers-15/feed/index.html’

100%[===================================================================================================>] 6,579       20.0KB/s   in 0.3s   

2017-07-22 22:29:13 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-15/feed/index.html’ saved [6579/6579]

--2017-07-22 22:29:15--  http://activehistory.ca/papers/history-papers-15/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-papers-15/?shared=email&msg=fail [following]
--2017-07-22 22:29:17--  http://activehistory.ca/papers/history-papers-15/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-15/index.html?share=email’

    [            <=>                                                                                     ] 86,033      20.0KB/s   in 4.2s   

2017-07-22 22:29:22 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-15/index.html?share=email’ saved [86033]

--2017-07-22 22:29:24--  http://activehistory.ca/papers/history-papers-15/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:29:24 ERROR 404: Not Found.

pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:29:26--  http://activehistory.ca/papers/history-papers-11/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 4497 (4.4K) [application/rss+xml]
activehistory.ca/papers/history-papers-11/feed: Not a directoryactivehistory.ca/papers/history-papers-11/feed/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-papers-11/feed/index.html’ (Not a directory).
--2017-07-22 22:29:28--  http://activehistory.ca/papers/history-papers-11/?share=email
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-papers-11/?shared=email&msg=fail [following]
--2017-07-22 22:29:30--  http://activehistory.ca/papers/history-papers-11/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-11/index.html?share=email’

    [            <=>                                                                                     ] 82,026      20.0KB/s   in 4.0s   

2017-07-22 22:29:34 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-11/index.html?share=email’ saved [82026]

--2017-07-22 22:29:36--  http://activehistory.ca/papers/history-papers-11/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:29:37 ERROR 404: Not Found.

--2017-07-22 22:29:39--  http://activehistory.ca/papers/history-paper-5/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 3778 (3.7K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/history-paper-5/feed/index.html’

100%[===================================================================================================>] 3,778       --.-K/s   in 0s      

2017-07-22 22:29:39 (235 MB/s) - ‘activehistory.ca/papers/history-paper-5/feed/index.html’ saved [3778/3778]

--2017-07-22 22:29:41--  http://activehistory.ca/papers/history-paper-5/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-paper-5/?shared=email&msg=fail [following]
--2017-07-22 22:29:43--  http://activehistory.ca/papers/history-paper-5/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-5/index.html?share=email’

    [              <=>                                                                                   ] 105,561     20.0KB/s   in 5.2s   

2017-07-22 22:29:48 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-5/index.html?share=email’ saved [105561]

--2017-07-22 22:29:50--  http://activehistory.ca/papers/history-paper-5/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:29:50 ERROR 404: Not Found.

--2017-07-22 22:29:52--  http://activehistory.ca/papers/history-papers-13/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [application/rss+xml]
Saving to: ‘activehistory.ca/papers/history-papers-13/feed/index.html’

    [  <=>                                                                                               ] 8,855       21.6KB/s   in 0.4s   

2017-07-22 22:29:53 (21.6 KB/s) - ‘activehistory.ca/papers/history-papers-13/feed/index.html’ saved [8855]

--2017-07-22 22:29:55--  http://activehistory.ca/papers/history-papers-13/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-papers-13/?shared=email&msg=fail [following]
--2017-07-22 22:29:57--  http://activehistory.ca/papers/history-papers-13/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-13/index.html?share=email’

    [          <=>                                                                                       ] 69,262      20.0KB/s   in 3.4s   

2017-07-22 22:30:01 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-13/index.html?share=email’ saved [69262]

--2017-07-22 22:30:03--  http://activehistory.ca/papers/history-papers-13/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:30:03 ERROR 404: Not Found.

--2017-07-22 22:30:05--  http://activehistory.ca/papers/papershistory-papers-17/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 4819 (4.7K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/papershistory-papers-17/feed/index.html’

100%[===================================================================================================>] 4,819       20.0KB/s   in 0.2s   

2017-07-22 22:30:06 (20.0 KB/s) - ‘activehistory.ca/papers/papershistory-papers-17/feed/index.html’ saved [4819/4819]

--2017-07-22 22:30:08--  http://activehistory.ca/papers/papershistory-papers-17/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/papershistory-papers-17/?shared=email&msg=fail [following]
--2017-07-22 22:30:10--  http://activehistory.ca/papers/papershistory-papers-17/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/papershistory-papers-17/index.html?share=email’

    [          <=>                                                                                       ] 70,447      20.0KB/s   in 3.4s   

2017-07-22 22:30:13 (20.0 KB/s) - ‘activehistory.ca/papers/papershistory-papers-17/index.html?share=email’ saved [70447]

--2017-07-22 22:30:15--  http://activehistory.ca/papers/papershistory-papers-17/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:30:16 ERROR 404: Not Found.

--2017-07-22 22:30:18--  http://activehistory.ca/papers/historypaper-9/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 1020 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/historypaper-9/feed/index.html’

100%[===================================================================================================>] 1,020       --.-K/s   in 0s      

2017-07-22 22:30:18 (85.7 MB/s) - ‘activehistory.ca/papers/historypaper-9/feed/index.html’ saved [1020/1020]

--2017-07-22 22:30:20--  http://activehistory.ca/papers/historypaper-9/%E2%80%9Chttp://pamplemoose.blogspot.com/2011/01/adventures-in-copyright-plea-for.html%E2%80%9Dblog%3C/a
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/2014/05/a-berks-retrospective-feminist-mentorship-and-inequality-in-the-ivory-tower/ [following]
--2017-07-22 22:30:22--  http://activehistory.ca/2014/05/a-berks-retrospective-feminist-mentorship-and-inequality-in-the-ivory-tower/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/historypaper-9/\342%80%9Chttp:/pamplemoose.blogspot.com/2011/01/adventures-in-copyright-plea-for.html\342%80%9Dblog</a’

    [       <=>                                                                                          ] 51,073      20.7KB/s   in 2.4s   

2017-07-22 22:30:24 (20.7 KB/s) - ‘activehistory.ca/papers/historypaper-9/\342%80%9Chttp:/pamplemoose.blogspot.com/2011/01/adventures-in-copyright-plea-for.html\342%80%9Dblog</a’ saved [51073]

--2017-07-22 22:30:26--  http://activehistory.ca/papers/historypaper-9/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/historypaper-9/?shared=email&msg=fail [following]
--2017-07-22 22:30:29--  http://activehistory.ca/papers/historypaper-9/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/historypaper-9/index.html?share=email’

    [         <=>                                                                                        ] 59,948      20.0KB/s   in 2.9s   

2017-07-22 22:30:32 (20.0 KB/s) - ‘activehistory.ca/papers/historypaper-9/index.html?share=email’ saved [59948]

--2017-07-22 22:30:34--  http://activehistory.ca/papers/historypaper-9/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:30:34 ERROR 404: Not Found.

--2017-07-22 22:30:36--  http://activehistory.ca/papers/history-paper-6/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 3487 (3.4K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/history-paper-6/feed/index.html’

100%[===================================================================================================>] 3,487       --.-K/s   in 0s      

2017-07-22 22:30:36 (244 MB/s) - ‘activehistory.ca/papers/history-paper-6/feed/index.html’ saved [3487/3487]

--2017-07-22 22:30:38--  http://activehistory.ca/papers/history-paper-6/j.mouhot@bham.ac.uk
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:30:38 ERROR 404: Not Found.

--2017-07-22 22:30:40--  http://activehistory.ca/papers/history-paper-6/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-paper-6/?shared=email&msg=fail [following]
--2017-07-22 22:30:42--  http://activehistory.ca/papers/history-paper-6/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-6/index.html?share=email’

    [           <=>                                                                                      ] 74,356      20.0KB/s   in 3.6s   

2017-07-22 22:30:46 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-6/index.html?share=email’ saved [74356]

--2017-07-22 22:30:48--  http://activehistory.ca/papers/history-paper-6/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:30:48 ERROR 404: Not Found.

--2017-07-22 22:30:50--  http://activehistory.ca/papers/history-papers-14/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 3129 (3.1K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/history-papers-14/feed/index.html’

100%[===================================================================================================>] 3,129       --.-K/s   in 0s      

2017-07-22 22:30:51 (203 MB/s) - ‘activehistory.ca/papers/history-papers-14/feed/index.html’ saved [3129/3129]

--2017-07-22 22:30:53--  http://activehistory.ca/papers/history-papers-14/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-papers-14/?shared=email&msg=fail [following]
--2017-07-22 22:30:55--  http://activehistory.ca/papers/history-papers-14/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-14/index.html?share=email’

    [             <=>                                                                                    ] 90,085      20.0KB/s   in 4.4s   

2017-07-22 22:31:00 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-14/index.html?share=email’ saved [90085]

--2017-07-22 22:31:02--  http://activehistory.ca/papers/history-papers-14/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:31:03 ERROR 404: Not Found.

--2017-07-22 22:31:05--  http://activehistory.ca/papers/history-papers-16/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 6630 (6.5K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/history-papers-16/feed/index.html’

100%[===================================================================================================>] 6,630       19.9KB/s   in 0.3s   

2017-07-22 22:31:05 (19.9 KB/s) - ‘activehistory.ca/papers/history-papers-16/feed/index.html’ saved [6630/6630]

--2017-07-22 22:31:07--  http://activehistory.ca/papers/history-papers-16/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-papers-16/?shared=email&msg=fail [following]
--2017-07-22 22:31:09--  http://activehistory.ca/papers/history-papers-16/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-16/index.html?share=email’

    [           <=>                                                                                      ] 74,636      20.0KB/s   in 3.6s   

2017-07-22 22:31:13 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-16/index.html?share=email’ saved [74636]

--2017-07-22 22:31:15--  http://activehistory.ca/papers/history-papers-16/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:31:15 ERROR 404: Not Found.

--2017-07-22 22:31:17--  http://activehistory.ca/papers/historypaper-10/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 1021 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/historypaper-10/feed/index.html’

100%[===================================================================================================>] 1,021       --.-K/s   in 0s      

2017-07-22 22:31:18 (50.3 MB/s) - ‘activehistory.ca/papers/historypaper-10/feed/index.html’ saved [1021/1021]

--2017-07-22 22:31:20--  http://activehistory.ca/papers/historypaper-10/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/historypaper-10/?shared=email&msg=fail [following]
--2017-07-22 22:31:22--  http://activehistory.ca/papers/historypaper-10/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/historypaper-10/index.html?share=email’

    [                <=>                                                                                 ] 117,793     20.0KB/s   in 5.8s   

2017-07-22 22:31:28 (20.0 KB/s) - ‘activehistory.ca/papers/historypaper-10/index.html?share=email’ saved [117793]

--2017-07-22 22:31:30--  http://activehistory.ca/papers/historypaper-10/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:31:30 ERROR 404: Not Found.

--2017-07-22 22:31:32--  http://activehistory.ca/papers/roundtable/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 2109 (2.1K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/roundtable/feed/index.html’

100%[===================================================================================================>] 2,109       --.-K/s   in 0s      

2017-07-22 22:31:32 (199 MB/s) - ‘activehistory.ca/papers/roundtable/feed/index.html’ saved [2109/2109]

--2017-07-22 22:31:34--  http://activehistory.ca/papers/roundtable/%22
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:31:34 ERROR 404: Not Found.

--2017-07-22 22:31:36--  http://activehistory.ca/papers/pbaskerville/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/pbaskerville/index.html’

    [         <=>                                                                                        ] 57,271      20.0KB/s   in 2.8s   

2017-07-22 22:31:39 (20.0 KB/s) - ‘activehistory.ca/papers/pbaskerville/index.html’ saved [57271]

--2017-07-22 22:31:41--  http://activehistory.ca/papers/ldick/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/ldick/index.html’

    [        <=>                                                                                         ] 60,002      20.0KB/s   in 2.9s   

2017-07-22 22:31:44 (20.0 KB/s) - ‘activehistory.ca/papers/ldick/index.html’ saved [60002]

--2017-07-22 22:31:46--  http://activehistory.ca/papers/aperr/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/aperr/index.html’

    [         <=>                                                                                        ] 58,258      20.0KB/s   in 2.8s   

2017-07-22 22:31:49 (20.0 KB/s) - ‘activehistory.ca/papers/aperr/index.html’ saved [58258]

--2017-07-22 22:31:51--  http://activehistory.ca/papers/rsandwell/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/rsandwell/index.html’

    [        <=>                                                                                         ] 58,132      21.3KB/s   in 2.7s   

2017-07-22 22:31:54 (21.3 KB/s) - ‘activehistory.ca/papers/rsandwell/index.html’ saved [58132]

--2017-07-22 22:31:56--  http://activehistory.ca/papers/roundtable/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/roundtable/?shared=email&msg=fail [following]
--2017-07-22 22:31:58--  http://activehistory.ca/papers/roundtable/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/roundtable/index.html?share=email’

    [          <=>                                                                                       ] 63,701      20.0KB/s   in 3.1s   

2017-07-22 22:32:01 (20.0 KB/s) - ‘activehistory.ca/papers/roundtable/index.html?share=email’ saved [63701]

--2017-07-22 22:32:03--  http://activehistory.ca/papers/roundtable/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:32:04 ERROR 404: Not Found.

--2017-07-22 22:32:06--  http://activehistory.ca/papers/the-home-archivist/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 929 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/the-home-archivist/feed/index.html’

100%[===================================================================================================>] 929         --.-K/s   in 0s      

2017-07-22 22:32:06 (52.0 MB/s) - ‘activehistory.ca/papers/the-home-archivist/feed/index.html’ saved [929/929]

--2017-07-22 22:32:08--  http://activehistory.ca/papers/the-home-archivist/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/the-home-archivist/?shared=email&msg=fail [following]
--2017-07-22 22:32:10--  http://activehistory.ca/papers/the-home-archivist/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/the-home-archivist/index.html?share=email’

    [       <=>                                                                                          ] 43,641      20.0KB/s   in 2.1s   

2017-07-22 22:32:12 (20.0 KB/s) - ‘activehistory.ca/papers/the-home-archivist/index.html?share=email’ saved [43641]

--2017-07-22 22:32:14--  http://activehistory.ca/papers/the-home-archivist/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:32:15 ERROR 404: Not Found.

--2017-07-22 22:32:17--  http://activehistory.ca/papers/historypaper-8/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 4818 (4.7K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/historypaper-8/feed/index.html’

100%[===================================================================================================>] 4,818       20.0KB/s   in 0.2s   

2017-07-22 22:32:17 (20.0 KB/s) - ‘activehistory.ca/papers/historypaper-8/feed/index.html’ saved [4818/4818]

--2017-07-22 22:32:19--  http://activehistory.ca/papers/historypaper-8/LaineyGossip.com
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:32:19 ERROR 404: Not Found.

--2017-07-22 22:32:21--  http://activehistory.ca/papers/historypaper-8/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/historypaper-8/?shared=email&msg=fail [following]
--2017-07-22 22:32:23--  http://activehistory.ca/papers/historypaper-8/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/historypaper-8/index.html?share=email’

    [           <=>                                                                                      ] 75,048      20.0KB/s   in 3.7s   

2017-07-22 22:32:27 (20.0 KB/s) - ‘activehistory.ca/papers/historypaper-8/index.html?share=email’ saved [75048]

--2017-07-22 22:32:29--  http://activehistory.ca/papers/historypaper-8/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:32:29 ERROR 404: Not Found.

--2017-07-22 22:32:31--  http://activehistory.ca/papers/what-can-oral-history-teach-us/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 3012 (2.9K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/what-can-oral-history-teach-us/feed/index.html’

100%[===================================================================================================>] 3,012       --.-K/s   in 0s      

2017-07-22 22:32:31 (188 MB/s) - ‘activehistory.ca/papers/what-can-oral-history-teach-us/feed/index.html’ saved [3012/3012]

--2017-07-22 22:32:33--  http://activehistory.ca/papers/wp-includes/js/tinymce/plugins/wpgallery/img/t.gif
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:32:34 ERROR 404: Not Found.

--2017-07-22 22:32:36--  http://activehistory.ca/papers/what-can-oral-history-teach-us/www.lifestoriesmontreal.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:32:36 ERROR 404: Not Found.

--2017-07-22 22:32:38--  http://activehistory.ca/papers/what-can-oral-history-teach-us/post.php?post=4058&action=edit&message=10
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:32:38 ERROR 404: Not Found.

--2017-07-22 22:32:40--  http://activehistory.ca/papers/papers/history-paper-3/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/history-paper-3/ [following]
--2017-07-22 22:32:42--  http://activehistory.ca/papers/history-paper-3/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/papers/history-paper-3/index.html’

    [             <=>                                                                                    ] 93,943      20.0KB/s   in 4.6s   

2017-07-22 22:32:47 (20.0 KB/s) - ‘activehistory.ca/papers/papers/history-paper-3/index.html’ saved [93943]

--2017-07-22 22:32:49--  http://activehistory.ca/papers/what-can-oral-history-teach-us/david.webster@uregina.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:32:49 ERROR 404: Not Found.

--2017-07-22 22:32:51--  http://activehistory.ca/papers/what-can-oral-history-teach-us/post.php?post=672&action=edit
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:32:51 ERROR 404: Not Found.

--2017-07-22 22:32:53--  http://activehistory.ca/papers/what-can-oral-history-teach-us/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/what-can-oral-history-teach-us/?shared=email&msg=fail [following]
--2017-07-22 22:32:56--  http://activehistory.ca/papers/what-can-oral-history-teach-us/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/what-can-oral-history-teach-us/index.html?share=email’

    [               <=>                                                                                  ] 109,189     20.0KB/s   in 5.3s   

2017-07-22 22:33:01 (20.0 KB/s) - ‘activehistory.ca/papers/what-can-oral-history-teach-us/index.html?share=email’ saved [109189]

--2017-07-22 22:33:03--  http://activehistory.ca/papers/what-can-oral-history-teach-us/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:33:03 ERROR 404: Not Found.

--2017-07-22 22:33:05--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [application/rss+xml]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/feed/index.html’

    [   <=>                                                                                              ] 12,604      20.0KB/s   in 0.6s   

2017-07-22 22:33:06 (20.0 KB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/feed/index.html’ saved [12604]

--2017-07-22 22:33:08--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-1-can-pop-hist-lit/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-1-can-pop-hist-lit/index.html’

    [    <=>                                                                                             ] 29,451      22.8KB/s   in 1.3s   

2017-07-22 22:33:10 (22.8 KB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-1-can-pop-hist-lit/index.html’ saved [29451]

--2017-07-22 22:33:12--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-2-chapters/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-2-chapters/index.html’

    [    <=>                                                                                             ] 29,416      22.8KB/s   in 1.3s   

2017-07-22 22:33:13 (22.8 KB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-2-chapters/index.html’ saved [29416]

--2017-07-22 22:33:15--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-3-chapters-expunged/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-3-chapters-expunged/index.html’

    [    <=>                                                                                             ] 29,747      23.0KB/s   in 1.3s   

2017-07-22 22:33:16 (23.0 KB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-3-chapters-expunged/index.html’ saved [29747]

--2017-07-22 22:33:18--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-4-can-pop-clock/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-4-can-pop-clock/index.html’

    [    <=>                                                                                             ] 29,292      22.7KB/s   in 1.3s   

2017-07-22 22:33:20 (22.7 KB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-4-can-pop-clock/index.html’ saved [29292]

--2017-07-22 22:33:22--  http://activehistory.ca/papers/papers/rsandwell/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: http://activehistory.ca/papers/rsandwell/ [following]
--2017-07-22 22:33:24--  http://activehistory.ca/papers/rsandwell/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/papers/rsandwell/index.html’

    [         <=>                                                                                        ] 58,132      20.0KB/s   in 2.8s   

2017-07-22 22:33:27 (20.0 KB/s) - ‘activehistory.ca/papers/papers/rsandwell/index.html’ saved [58132]

--2017-07-22 22:33:29--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/?shared=email&msg=fail [following]
--2017-07-22 22:33:31--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/index.html?share=email’

    [          <=>                                                                                       ] 75,883      20.0KB/s   in 3.7s   

2017-07-22 22:33:35 (20.0 KB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/index.html?share=email’ saved [75883]

--2017-07-22 22:33:37--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:33:38 ERROR 404: Not Found.

--2017-07-22 22:33:40--  http://activehistory.ca/papers/history-papers-12/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [application/rss+xml]
Saving to: ‘activehistory.ca/papers/history-papers-12/feed/index.html’

    [   <=>                                                                                              ] 17,479      20.0KB/s   in 0.9s   

2017-07-22 22:33:41 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-12/feed/index.html’ saved [17479]

--2017-07-22 22:33:43--  http://activehistory.ca/papers/history-papers-12/1_edn1
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:33:43 ERROR 404: Not Found.

--2017-07-22 22:33:45--  http://activehistory.ca/papers/history-papers-12/%22
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:33:45 ERROR 404: Not Found.

--2017-07-22 22:33:47--  http://activehistory.ca/papers/history-papers-12/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-papers-12/?shared=email&msg=fail [following]
--2017-07-22 22:33:49--  http://activehistory.ca/papers/history-papers-12/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-papers-12/index.html?share=email’

    [             <=>                                                                                    ] 108,373     20.0KB/s   in 5.3s   

2017-07-22 22:33:55 (20.0 KB/s) - ‘activehistory.ca/papers/history-papers-12/index.html?share=email’ saved [108373]

--2017-07-22 22:33:57--  http://activehistory.ca/papers/history-papers-12/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:33:57 ERROR 404: Not Found.

--2017-07-22 22:33:59--  http://activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 955 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/feed/index.html’

100%[===================================================================================================>] 955         --.-K/s   in 0s      

2017-07-22 22:33:59 (73.3 MB/s) - ‘activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/feed/index.html’ saved [955/955]

--2017-07-22 22:34:01--  http://activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/?shared=email&msg=fail [following]
--2017-07-22 22:34:03--  http://activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/index.html?share=email’

    [       <=>                                                                                          ] 44,191      20.0KB/s   in 2.2s   

2017-07-22 22:34:06 (20.0 KB/s) - ‘activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/index.html?share=email’ saved [44191]

--2017-07-22 22:34:08--  http://activehistory.ca/papers/anishinaabeg-in-the-war-of-1812/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:34:08 ERROR 404: Not Found.

pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:34:10--  http://activehistory.ca/papers/history-paper-2/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 6093 (6.0K) [application/rss+xml]
activehistory.ca/papers/history-paper-2/feed: Not a directoryactivehistory.ca/papers/history-paper-2/feed/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-paper-2/feed/index.html’ (Not a directory).
--2017-07-22 22:34:12--  http://activehistory.ca/papers/history-paper-2/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:34:12 ERROR 404: Not Found.

--2017-07-22 22:34:14--  http://activehistory.ca/papers/history-paper-2/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-paper-2/?shared=email&msg=fail [following]
--2017-07-22 22:34:16--  http://activehistory.ca/papers/history-paper-2/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-2/index.html?share=email’

    [           <=>                                                                                      ] 80,922      20.0KB/s   in 4.0s   

2017-07-22 22:34:20 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-2/index.html?share=email’ saved [80922]

--2017-07-22 22:34:22--  http://activehistory.ca/papers/history-paper-1/feed/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: 2127 (2.1K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/history-paper-1/feed/index.html’

100%[===================================================================================================>] 2,127       --.-K/s   in 0s      

2017-07-22 22:34:23 (204 MB/s) - ‘activehistory.ca/papers/history-paper-1/feed/index.html’ saved [2127/2127]

--2017-07-22 22:34:25--  http://activehistory.ca/papers/history-paper-1/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:34:25 ERROR 404: Not Found.

--2017-07-22 22:34:27--  http://activehistory.ca/papers/history-paper-1/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-paper-1/?shared=email&msg=fail [following]
--2017-07-22 22:34:29--  http://activehistory.ca/papers/history-paper-1/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-1/index.html?share=email’

    [          <=>                                                                                       ] 70,915      20.0KB/s   in 3.5s   

2017-07-22 22:34:32 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-1/index.html?share=email’ saved [70915]

--2017-07-22 22:34:34--  http://activehistory.ca/papers/history-paper-4/feed/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: 3077 (3.0K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/history-paper-4/feed/index.html’

100%[===================================================================================================>] 3,077       --.-K/s   in 0s      

2017-07-22 22:34:35 (202 MB/s) - ‘activehistory.ca/papers/history-paper-4/feed/index.html’ saved [3077/3077]

--2017-07-22 22:34:37--  http://activehistory.ca/papers/history-paper-4/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-paper-4/?shared=email&msg=fail [following]
--2017-07-22 22:34:39--  http://activehistory.ca/papers/history-paper-4/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-4/index.html?share=email’

    [          <=>                                                                                       ] 66,846      20.0KB/s   in 3.3s   

2017-07-22 22:34:42 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-4/index.html?share=email’ saved [66846]

--2017-07-22 22:34:44--  http://activehistory.ca/papers/history-paper-4/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:34:44 ERROR 404: Not Found.

--2017-07-22 22:34:46--  http://activehistory.ca/papers/themes/international/vietnam-et-cuba/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 1813 (1.8K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/themes/international/vietnam-et-cuba/feed/index.html’

100%[===================================================================================================>] 1,813       --.-K/s   in 0s      

2017-07-22 22:34:46 (90.3 MB/s) - ‘activehistory.ca/papers/themes/international/vietnam-et-cuba/feed/index.html’ saved [1813/1813]

--2017-07-22 22:34:48--  http://activehistory.ca/papers/themes/international/vietnam-et-cuba/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/themes/international/vietnam-et-cuba/?shared=email&msg=fail [following]
--2017-07-22 22:34:51--  http://activehistory.ca/papers/themes/international/vietnam-et-cuba/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/themes/international/vietnam-et-cuba/index.html?share=email’

    [          <=>                                                                                       ] 66,355      20.0KB/s   in 3.2s   

2017-07-22 22:34:54 (20.0 KB/s) - ‘activehistory.ca/papers/themes/international/vietnam-et-cuba/index.html?share=email’ saved [66355]

--2017-07-22 22:34:56--  http://activehistory.ca/papers/themes/international/vietnam-et-cuba/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:34:56 ERROR 404: Not Found.

pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:34:58--  http://activehistory.ca/papers/history-paper-3/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 3739 (3.7K) [application/rss+xml]
activehistory.ca/papers/history-paper-3/feed: Not a directoryactivehistory.ca/papers/history-paper-3/feed/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-paper-3/feed/index.html’ (Not a directory).
--2017-07-22 22:35:00--  http://activehistory.ca/papers/history-paper-3/david.webster@uregina.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:35:00 ERROR 404: Not Found.

pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:35:02--  http://activehistory.ca/papers/history-paper-3/figure-1/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/history-paper-3/figure-1: Not a directoryactivehistory.ca/papers/history-paper-3/figure-1/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-paper-3/figure-1/index.html’ (Not a directory).
pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:35:05--  http://activehistory.ca/papers/history-paper-3/figure-2/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/history-paper-3/figure-2: Not a directoryactivehistory.ca/papers/history-paper-3/figure-2/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-paper-3/figure-2/index.html’ (Not a directory).
pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:35:07--  http://activehistory.ca/papers/history-paper-3/figure-3/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/history-paper-3/figure-3: Not a directoryactivehistory.ca/papers/history-paper-3/figure-3/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-paper-3/figure-3/index.html’ (Not a directory).
pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:35:09--  http://activehistory.ca/papers/history-paper-3/figure-4/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/history-paper-3/figure-4: Not a directoryactivehistory.ca/papers/history-paper-3/figure-4/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-paper-3/figure-4/index.html’ (Not a directory).
pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:35:11--  http://activehistory.ca/papers/history-paper-3/figure-5/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/history-paper-3/figure-5: Not a directoryactivehistory.ca/papers/history-paper-3/figure-5/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-paper-3/figure-5/index.html’ (Not a directory).
pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:35:13--  http://activehistory.ca/papers/history-paper-3/figure-6/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/history-paper-3/figure-6: Not a directoryactivehistory.ca/papers/history-paper-3/figure-6/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-paper-3/figure-6/index.html’ (Not a directory).
pathconf: Not a directory
pathconf: Not a directory
--2017-07-22 22:35:16--  http://activehistory.ca/papers/history-paper-3/figure-7/
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
activehistory.ca/papers/history-paper-3/figure-7: Not a directoryactivehistory.ca/papers/history-paper-3/figure-7/index.html: Not a directory

Cannot write to ‘activehistory.ca/papers/history-paper-3/figure-7/index.html’ (Not a directory).
--2017-07-22 22:35:18--  http://activehistory.ca/papers/history-paper-3/?share=email
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/history-paper-3/?shared=email&msg=fail [following]
--2017-07-22 22:35:20--  http://activehistory.ca/papers/history-paper-3/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/history-paper-3/index.html?share=email’

    [             <=>                                                                                    ] 94,113      20.0KB/s   in 4.6s   

2017-07-22 22:35:25 (20.0 KB/s) - ‘activehistory.ca/papers/history-paper-3/index.html?share=email’ saved [94113]

--2017-07-22 22:35:27--  http://activehistory.ca/papers/history-paper-3/info@activehistory.ca
Connecting to activehistory.ca (activehistory.ca)|138.197.156.41|:80... connected.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:35:27 ERROR 404: Not Found.

--2017-07-22 22:35:29--  http://activehistory.ca/papers/200-years-of-the-old-chieftain/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 953 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/200-years-of-the-old-chieftain/feed/index.html’

100%[===================================================================================================>] 953         --.-K/s   in 0s      

2017-07-22 22:35:29 (106 MB/s) - ‘activehistory.ca/papers/200-years-of-the-old-chieftain/feed/index.html’ saved [953/953]

--2017-07-22 22:35:31--  http://activehistory.ca/papers/200-years-of-the-old-chieftain/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/200-years-of-the-old-chieftain/?shared=email&msg=fail [following]
--2017-07-22 22:35:33--  http://activehistory.ca/papers/200-years-of-the-old-chieftain/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/200-years-of-the-old-chieftain/index.html?share=email’

    [       <=>                                                                                          ] 43,985      20.0KB/s   in 2.1s   

2017-07-22 22:35:35 (20.0 KB/s) - ‘activehistory.ca/papers/200-years-of-the-old-chieftain/index.html?share=email’ saved [43985]

--2017-07-22 22:35:37--  http://activehistory.ca/papers/200-years-of-the-old-chieftain/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:35:38 ERROR 404: Not Found.

--2017-07-22 22:35:40--  http://activehistory.ca/papers/pbaskerville/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 2178 (2.1K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/pbaskerville/feed/index.html’

100%[===================================================================================================>] 2,178       --.-K/s   in 0s      

2017-07-22 22:35:40 (263 MB/s) - ‘activehistory.ca/papers/pbaskerville/feed/index.html’ saved [2178/2178]

--2017-07-22 22:35:42--  http://activehistory.ca/papers/pbaskerville/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/pbaskerville/?shared=email&msg=fail [following]
--2017-07-22 22:35:44--  http://activehistory.ca/papers/pbaskerville/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/pbaskerville/index.html?share=email’

    [         <=>                                                                                        ] 57,441      20.0KB/s   in 2.8s   

2017-07-22 22:35:47 (20.0 KB/s) - ‘activehistory.ca/papers/pbaskerville/index.html?share=email’ saved [57441]

--2017-07-22 22:35:49--  http://activehistory.ca/papers/pbaskerville/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:35:49 ERROR 404: Not Found.

--2017-07-22 22:35:51--  http://activehistory.ca/papers/ldick/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 965 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/ldick/feed/index.html’

100%[===================================================================================================>] 965         --.-K/s   in 0s      

2017-07-22 22:35:51 (119 MB/s) - ‘activehistory.ca/papers/ldick/feed/index.html’ saved [965/965]

--2017-07-22 22:35:53--  http://activehistory.ca/papers/ldick/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/ldick/?shared=email&msg=fail [following]
--2017-07-22 22:35:55--  http://activehistory.ca/papers/ldick/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/ldick/index.html?share=email’

    [         <=>                                                                                        ] 60,172      20.0KB/s   in 2.9s   

2017-07-22 22:35:59 (20.0 KB/s) - ‘activehistory.ca/papers/ldick/index.html?share=email’ saved [60172]

--2017-07-22 22:36:01--  http://activehistory.ca/papers/ldick/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:36:01 ERROR 404: Not Found.

--2017-07-22 22:36:03--  http://activehistory.ca/papers/aperr/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 2256 (2.2K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/aperr/feed/index.html’

100%[===================================================================================================>] 2,256       --.-K/s   in 0s      

2017-07-22 22:36:03 (187 MB/s) - ‘activehistory.ca/papers/aperr/feed/index.html’ saved [2256/2256]

--2017-07-22 22:36:05--  http://activehistory.ca/papers/aperr/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/aperr/?shared=email&msg=fail [following]
--2017-07-22 22:36:07--  http://activehistory.ca/papers/aperr/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/aperr/index.html?share=email’

    [         <=>                                                                                        ] 58,428      20.0KB/s   in 2.9s   

2017-07-22 22:36:10 (20.0 KB/s) - ‘activehistory.ca/papers/aperr/index.html?share=email’ saved [58428]

--2017-07-22 22:36:12--  http://activehistory.ca/papers/aperr/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:36:12 ERROR 404: Not Found.

--2017-07-22 22:36:14--  http://activehistory.ca/papers/rsandwell/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 3079 (3.0K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/rsandwell/feed/index.html’

100%[===================================================================================================>] 3,079       --.-K/s   in 0s      

2017-07-22 22:36:15 (114 MB/s) - ‘activehistory.ca/papers/rsandwell/feed/index.html’ saved [3079/3079]

--2017-07-22 22:36:17--  http://activehistory.ca/papers/rsandwell/?share=email
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 302 Found
Location: http://activehistory.ca/papers/rsandwell/?shared=email&msg=fail [following]
--2017-07-22 22:36:19--  http://activehistory.ca/papers/rsandwell/?shared=email&msg=fail
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/rsandwell/index.html?share=email’

    [         <=>                                                                                        ] 58,302      20.0KB/s   in 2.8s   

2017-07-22 22:36:22 (20.0 KB/s) - ‘activehistory.ca/papers/rsandwell/index.html?share=email’ saved [58302]

--2017-07-22 22:36:24--  http://activehistory.ca/papers/rsandwell/info@activehistory.ca
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 404 Not Found
2017-07-22 22:36:24 ERROR 404: Not Found.

--2017-07-22 22:36:26--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-1-can-pop-hist-lit/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 1043 (1.0K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-1-can-pop-hist-lit/feed/index.html’

100%[===================================================================================================>] 1,043       --.-K/s   in 0s      

2017-07-22 22:36:26 (81.3 MB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-1-can-pop-hist-lit/feed/index.html’ saved [1043/1043]

--2017-07-22 22:36:28--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/figure-4-can-pop-clock/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/figure-4-can-pop-clock/index.html’

    [    <=>                                                                                             ] 29,443      22.8KB/s   in 1.3s   

2017-07-22 22:36:30 (22.8 KB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/figure-4-can-pop-clock/index.html’ saved [29443]

--2017-07-22 22:36:32--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-2-chapters/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 1021 [application/rss+xml]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-2-chapters/feed/index.html’

100%[===================================================================================================>] 1,021       --.-K/s   in 0s      

2017-07-22 22:36:32 (79.1 MB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-2-chapters/feed/index.html’ saved [1021/1021]

--2017-07-22 22:36:34--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-3-chapters-expunged/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 1039 (1.0K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-3-chapters-expunged/feed/index.html’

100%[===================================================================================================>] 1,039       --.-K/s   in 0s      

2017-07-22 22:36:34 (76.1 MB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-3-chapters-expunged/feed/index.html’ saved [1039/1039]

--2017-07-22 22:36:36--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-4-can-pop-clock/feed/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: 1031 (1.0K) [application/rss+xml]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-4-can-pop-clock/feed/index.html’

100%[===================================================================================================>] 1,031       --.-K/s   in 0s      

2017-07-22 22:36:36 (80.7 MB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/afigure-4-can-pop-clock/feed/index.html’ saved [1031/1031]

--2017-07-22 22:36:38--  http://activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/figure-1-can-pop-hist-lit/
Reusing existing connection to activehistory.ca:80.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/figure-1-can-pop-hist-lit/index.html’

    [    <=>                                                                                             ] 29,411      22.8KB/s   in 1.3s   

2017-07-22 22:36:40 (22.8 KB/s) - ‘activehistory.ca/papers/a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada/figure-1-can-pop-hist-lit/index.html’ saved [29411]

FINISHED --2017-07-22 22:36:40--
Total wall clock time: 18m 47s
Downloaded: 178 files, 7.6M in 6m 26s (20.3 KB/s)
ktamg2@1b6946be137d:~/wget-activehistory$ ls
activehistory.ca  index.html
ktamg2@1b6946be137d:~/wget-activehistory$ cd activehistory.ca/
ktamg2@1b6946be137d:~/wget-activehistory/activehistory.ca$ ls
papers  robots.txt
ktamg2@1b6946be137d:~/wget-activehistory/activehistory.ca$ cd papers
ktamg2@1b6946be137d:~/wget-activehistory/activehistory.ca/papers$ ls
200-years-of-the-old-chieftain
anishinaabeg-in-the-war-of-1812
aperr
a-polyphony-of-synthesizers-why-every-historian-of-canada-should-write-a-history-of-canada
bodies-of-water-not-bodies-of-women-canadian-media-images-of-the-idle-no-more-movement
canadas-first-world-war-a-centennial-series-on-activehistory-ca
commemorating-35-years-of-the-marathon-of-hope
disappearing-into-white-space-indigenous-toronto-1900-1914
history-paper-1
historypaper-10
history-paper-2
history-paper-3
history-paper-4
history-paper-5
history-paper-6
historypaper-8
historypaper-9
history-papers-11
history-papers-12
history-papers-13
history-papers-14
history-papers-15
history-papers-16
index.html
index.html?share=email
indigenous-histories
ldick
paper-20
papers
papershistory-papers-17
papershistory-papers-19
pbaskerville
recognizing-the-historical-thinking-project
refugees-in-historical-perspective
roundtable
rsandwell
the-contemporary-relevance-of-the-historical-treaties-to-treaty-indian-peoples
the-home-archivist
themes
theme-week-infectious-disease-contagion-and-the-history-of-vaccines
the-royal-proclamation-in-historical-context
the-social-democracy-question
truth-reconciliation-and-the-politics-of-the-body-in-indian-residential-school-history
what-can-oral-history-teach-us
ktamg2@1b6946be137d:~/wget-activehistory/activehistory.ca/papers$ 