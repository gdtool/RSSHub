---
pageClass: routes
---

# University

## MIT

### MIT graduateadmissions's all blogs

<RouteEn author="LogicJake" example="/mit/graduateadmissions/index/all" path="/mit/graduateadmissions/index/all"/>

### MIT graduateadmissions's blogs by department

<RouteEn author="LogicJake" example="/mit/graduateadmissions/department/eecs" path="/mit/graduateadmissions/department/:name" :paramsDesc="['department name which can be found in url']"/>

### MIT graduateadmissions's blogs by category

<RouteEn author="LogicJake" example="/mit/graduateadmissions/category/beyond-the-lab" path="/mit/graduateadmissions/category/:name" :paramsDesc="['category name which can be found in url']"/>

## Polimi

### News

<RouteEn author="exuanbo" example="/polimi/news" path="/polimi/news/:language?" :paramsDesc="['English language code en']" />

## UMASS Amherst

### College of Electrical and Computer Engineering News

<RouteEn author="gammapi" example="/umass/amherst/ecenews" path="/umass/amherst/ecenews" radar="1"/>

### College of Information & Computer Sciences News

<RouteEn author="gammapi" example="/umass/amherst/csnews" path="/umass/amherst/csnews" radar="1"/>
