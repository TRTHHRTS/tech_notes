## Проrраммист-прагматик
### Заметки по прочтению
- важно не только ждать обратную связь, а активно ее запрашивать, если она вам важна! (речь про выполняемые задачи и постоянный контанкт с заказчиками и клиентами);
- важно подавать свои идеи в привлекательной форме (то есть нужно доносить свои мысли/предложения в поятной для заказчика форме);
- нужно находить соответствующий момент, когда тебя наиболее слушают (то есть даже если у твоих доводов есть вес, нужно все равно искать момент "наилучшего применения силы");
- следует отличать дублирование от совпадения! Первое лучше не допускать, а второе - можно, это норма;
- нельзя полагаться на свойства объектов, которые вам неподвластны, например, номер телефона клиента (и делать номер телефона уникальным ID);
- лучше разрабатывать постепенно и показывать находу результат заказчикам (регулярные демо и постоянныый сбор ОС на каждом этапе помогут в итоге сделать и быстрее и качественнее);
- не важно чей баг, если тебе исправлять - то проблема твоя (то есть если это не ваш личный репозиторий - то и код не ваш личный, а значит за него отвечают сразу все, в той или иной степени, а значит все, что туда попало - коллективная ответственность и забота);
- на любой баг если написать тест, чтобы в дальнейшем не было его (то есть не просто исправить баг, а именно что воспроизвести в тесте, исправить и оставить тест для того, чтобы больше не случилось - потому что иначе - обязательно случится!);
- optional как цепочки преобразования кода это хорошо, их мы используем (единообразие подхода к обработке/изменению потока информации)! И обработка ошибок там есть общая для всего конвейера;
- наследование это не очень хорошо, лучше без него, потому что это повышает coupling (всегда можно сделать через интерфейсы, так coupling будет ниже);
- выполнять рефакторинг мелкими шагами и лучше сразу как только нашли (отдельными коммитами как минимум, а лучше отдельными MR);
- может быть заложить 2-3сп в каждый спринт, чтобы как раз проводить такой рефакторинг любому члену команды? (как идея для обсуждения внутри команды);
- тесты писать хорошо не потому, что они что-то в итоге будут проверять (хотя в этом тоже есть прок), а потому, что пока ты пишешь правильный тест - ты уже проверяешь код и повышаешь его качество, просто обдумыванием теста к нему!
- тесты на основе свойств - когда ты описываешь признаки метода/модуля и тестируешь то что эти свойства корректны после выполнения метода (например, длина массива при методе сортировки - она не должна меняться);
