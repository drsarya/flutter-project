# Бесконечная лента изображений из сервиса Flickr

В приложении используется **redux** для хранения состояния приложения.

Карточка объекта представлена фотографией, описанием и счетчиком лайков. При полноэкранном просмотре фотографии состояние карточки меняется и сохраняется в глобальном состоянии, поэтому при переходе обратно, лента содержит уже обновлённые значения.

Бесконечная лента основана на индексе списка карточек: если до конца ленты остаётся меньше n-элементов, производится подгрузка новой страницы. При этом ранее просмотренные элементы остаются в глобальном состоянии.  



На видео с демонстрацией работы приложения в правой части отображаются логи, сигнализирующие о подгрзуке данных и событиях лайков. 









https://github.com/drsarya/flutter-feed/assets/63103401/1ec773a9-062a-4f7c-a5e9-444377cd30fa

