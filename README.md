# books-project


Получилось что есть три сценария:

- гость может ставить лайки (т.е. добавлять в избранное). Инфа о его действиях живет пока живет вкладка

- зареганный юзер (юзер регается автоматически когда вводит логин, которого нет в базе данных) - он может делать тоже самое что гость, только его действия сохраняются в БД. Так же он может сменить ник и аватарку

- админ - может делать тоже самое, что юзер, плюс имеет доступ к удалению/добавлению книг и удалению/добавлению юзеров

Думаю добавить функционал по добавлению и удалению авторов.
И на главной странице есть фильтр, у него еще нет функционала.

Из минусов - AirTable в отличие от Firebase не является симуляцией бэка, в частности там нет методов авторизации. Поэтому авторизация примитивная и легко взламывается - легко получить доступ ко всем пользователям. Сайт не хакерозащищенный.

Из плюсов - симпатично получилось

Так как я писал изначально для Яши - я не юзал фреймворки, всё на ванильном JS. С React или Vue получился бы лучший перфоманс и примерно в два раза меньше кода. Но для понимания ванильный JS проще

Если у вас будут вопросы - обязательно спрашивайте, я с удовольствием отвечу)
