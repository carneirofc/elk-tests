# logstash
ref: https://streamsets.com/documentation/datacollector/latest/help/datacollector/UserGuide/Apx-GrokPatterns/GrokPatterns_title.html

pattern 

localhost:45540 Thu Dec 12 13:45:35 2019 12-Dec-19 13:45:26 lnlsfac-srv1 sirius BO-48D:PU-EjeKckr:Voltage-SP new=2729.55 old=2729.554

WIP

^%{HOSTPORT:ioc_host} %{DAY} %{MONTH} %{POSINT} %{POSINT}:%{POSINT}:%{POSINT} %{POSINT} %{POSINT:day}-%{MONTH:month}-%{POSINT:year}

