♦his install:Drop modules from darkrp




change text to "change server"

MrKuBu Server - hostname

Player see: MrKuBu Server[Change]

--Example(пример)For ru:

if SERVER then

local o = 'MrKuBu Server'

local names = {'Добро пожаловать',

'У нас круто',

'У нас набор',

'АРЦ бомбит',

'Кейк банит',

'Сделал MrKuBu',

'Много профессий',

'Добрая администрация',

'Привет! Заходи к нам',

'Добавь в избранное',

'Наш сайт MrKuBu.github.io',

'У нас свои аддоны',

'Стим версия сервера',

'Мощный сервер',}

timer.Create('ChangeHstname',7,0,function() 

local avs = (o..'['..table.Random(names)..']')

 RunConsoleCommand('hostname',avs) 
 
 end)
 
end

