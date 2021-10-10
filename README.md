[Softtour](https://www.softtour.by/).

#Functional Test Cases

## Test case 1
  Steps:  
    1. Go to https://www.softtour.by/round-selection  
    2. Click "Подобрать" button. 
    3. Select "Дата" in "Сортировать по" field.<br> 
    4. In "А-я" toggle arrow down.<br> 
  Expected Result:<br>  
    List of hotels sorted by date from early to late. 
    
## Test case 2
  Steps:<br>  
    1. Go to https://www.softtour.by/round-selection.<br> 
    2. Click "Подобрать" button.<br> 
    3. In search section "РЕЗУЛЬТАТЫ ПОИСКА С ВОЗМОЖНОСТЬЮ ФИЛЬТРАЦИИ, СОРТИРОВКИ" select "4" in "Рейтинг от".<br> 
    4. In search section "РЕЗУЛЬТАТЫ ПОИСКА С ВОЗМОЖНОСТЬЮ ФИЛЬТРАЦИИ, СОРТИРОВКИ" set "2000" in "Цена от" and "2400" in "Цена до".<br> 
    5. In search section "РЕЗУЛЬТАТЫ ПОИСКА С ВОЗМОЖНОСТЬЮ ФИЛЬТРАЦИИ, СОРТИРОВКИ" click "Применить".<br> 
  Expected Result:<br>  
    List of hotels whose price is from 2000 to 2400. 
    
 ## Test case 3. 
   Steps:<br>  
    1. Go to https://www.softtour.by/tours/promotion.<br> 
    2. Click "Показать" button. <br>
   Expected Result:  <br>
    In search list display message "Нет найденных туров". 
 
 ## Test case 4. 
   Steps:  <br>
    1. Go to https://www.softtour.by/hotels/turkey/viva-ulaslar-hotel-4. <br>
    2. Click "Отель в Google" button. <br>
   Expected Result:  <br>
    Yandex map is replaced with Google maps. 

 ## Test case 5. 
   Steps:  <br>
    1. Go to https://www.softtour.by/. <br>
    2. Click "Подобрать" button. <br>
   Expected Result:  <br>
    Should be redirect to https://www.softtour.by/round-selection/uae. 
    
 ## Test case 6. 
   Steps:  <br>
    1. Go to https://www.softtour.by/round-selection. <br>
    2. In "Страна" section select "Транзания". <br>
   Expected Result:  <br>
    Should be redirect to https://www.softtour.by/round-selection/tanzania. 

## Test case 7
   Steps:<br>
    1. Go to https://www.softtour.by/round-selection<br>
    2. In "Страна" section select "Транзания"<br>
   Expected Result:<br>
    Title of page is replaced with "Подбор тура в Танзанию из Минска, Москвы и Киева в режиме онлайн"
    
## Test case 8
   Steps:<br>
    1. Go to https://www.softtour.by/round-selection<br>
    2. In subtitle section click red text "Как пользоваться подбором тура?"<br>
   Expected Result:<br>
    The instruction must be display as drop-down section
    
## Test case 9
   Steps:<br>
    1. Go to https://www.softtour.by/<br>
    2. Navigate to fourth slide in slider<br>
    3. Click "Подробнее" link<br>
   Expected Result:<br>
    You will be redirect to https://www.softtour.by/tour/country/egypt/hot/town/minsk/usd/net/albatros/category/4*,5*/food/ai,uai
    
## Test case 10
   Steps:<br>
    1. Go to https://www.softtour.by/hotels/turkey/larissa-blue-3<br>
    2. Click "Оставить заявку"<br>
    3. In pop-up window click "Отправить"<br>
   Expected Result:<br>
    Validation of required field "Контактный телефон" is show
