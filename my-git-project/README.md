require 'nokogiri'
require 'open-uri'
Nokogiri::HTML(html)
doc = Nokogiri::HTML(open("https://flatironschool.com/"))
doc.css(".site-header__hero__headline")