# web-crawler
This is a java application.

By default the website to crawl is set to http://www.mi.com/in

Using this program one can search for keywords and the program will rank pages on http://www.mi.com/in based on the number of times the keyword occurs on the page.

To restrict the program from running indefinately the depth for parsing urls is set to 1

Eg. usage: to search for keywords memory and camera on http://www.mi.com/in run the program in command line with arguments: memory camera

ThreadCreator is the main class.

Eg. ouput
Ranking for Search String: memory
Key : http://www.mi.com/in/redmi3s/ Value : 1
Key : http://www.businesstoday.in/technology/reviews/xiaomi-redmi-note-4-review-improvising-perfection/story/244513.html Value : 2
Key : http://www.gizmodo.in/indiamodo/Review-Just-Go-And-Buy-The-Xiaomi-Redmi-3S-Prime/articleshow/53523786.cms Value : 2
Key : http://www.mi.com/in/redmi3splus/ Value : 1
Key : http://www.mi.com/in/service/miprotect/ Value : 1
Key : http://www.mi.com/in/note4/ Value : 1
Key : http://www.mi.com/in/note3/ Value : 1

Ranking for Search String: camera
Key : http://www.mi.com/en/ Value : 1
Key : http://www.businesstoday.in/technology/reviews/xiaomi-redmi-note-4-review-improvising-perfection/story/244513.html Value : 6
Key : http://www.mi.com/in/mimax/ Value : 2
Key : http://www.mi.com/in/service/warranty/ Value : 1
Key : http://buy.mi.com/in/site/logout Value : 2
Key : http://www.dailyo.in/technology/xiaomi-mi-max-smartphones-battery-life-galaxy-note/story/1/11450.html Value : 1
Key : http://www.mi.com/sg/ Value : 2
Key : http://www.mi.com/in/mi4/ Value : 1
Key : http://en.miui.com/forum/in Value : 1
Key : http://www.mi.com/in Value : 1
Key : https://play.google.com/store/apps/details?id=com.mi.global.shop&referrer=utm_source%3Dpc%26utm_medium%3Dbanner%26anid%3Dadmob Value : 2
Key : http://www.mi.com/in/ Value : 2
Key : http://www.mi.com/in/note3/ Value : 3
Key : http://www.mi.com/in/redmi3s/ Value : 6
Key : http://www.mi.com/in/pb10000/ Value : 1
Key : http://www.mi.com/in/index.html Value : 1
Key : http://www.mi.com/in/mi4i/ Value : 4
Key : http://www.mi.com/in/redmi3splus/ Value : 6
Key : http://www.mi.com/in/pb10000pro/ Value : 1
Key : http://www.mi.com/my/ Value : 3
Key : http://www.gizmodo.in/indiamodo/Review-Just-Go-And-Buy-The-Xiaomi-Redmi-3S-Prime/articleshow/53523786.cms Value : 3
Key : http://www.bgr.in/reviews/xiaomi-redmi-note-3-review-the-game-changer-again/ Value : 11
Key : http://www.mi.com/in/mi5/ Value : 4
Key : http://www.livemint.com/Consumer/zirc8i0M5bksidFpXJKqIJ/Review-Xiaomi-Mi-5-can-be-the-genuine-flagship-killer.html Value : 3
Key : http://www.mi.com/in/note4/ Value : 5
Key : http://www.mi.com/in/about/privacy/ Value : 1
