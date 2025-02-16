---
name: Накамоти
description: Node Running Made Easy - Как настроить и использовать Nakamochi Bitcoin и Lightning node.
---
Запуск собственного узла Bitcoin и Lightning больше не должен быть сложной задачей, доступной только техническим специалистам. Традиционно создание и управление узлами требовало глубоких знаний в области криптографии, сетевых технологий и разработки программного обеспечения. Nakamochi меняет эту ситуацию, делая узлы доступными для всех, независимо от технической подготовки.

С помощью Nakamochi каждый может создать и управлять узлом из дома, обеспечивая полную конфиденциальность и финансовую независимость. Запуск полноценного узла не только обеспечивает безопасность ваших собственных транзакций, но и способствует укреплению сети Биткойн. Децентрализованная и устойчивая сеть Биткойн опирается на широкое распределение узлов для обеспечения своей безопасности и независимости.

### Оглавление


- Что такое Nakamochi и как она работает?
- Создание Накамоти
- О сети Lightning Network
- Открытие каналов и совершение транзакций в сети Lightning Network

## Что такое Nakamochi и как она работает?

Nakamochi - это полноценный узел, работающий только с биткоином и поддерживающий сети Bitcoin и Lightning. Он включает в себя интегрированный кошелек Bitcoin и Lightning, что позволяет пользователям запускать безопасный, суверенный узел Bitcoin, пользуясь преимуществами скорости и низкой стоимости транзакций в сети Lightning Network.

Управление узлом Nakamochi осуществляется через мобильные приложения [BitBanana (Android)](https://bitbanana.app) и [Zeus (iOS)](https://bitbanana.app), что позволяет вам удобно управлять им из любого места. Эти приложения выступают в роли пульта дистанционного управления для вашего узла, позволяя вам напрямую платить биткойнами или Lightning, управлять транзакциями, открывать или закрывать каналы, проверять баланс и следить за работой узла - все это с легкостью.

## Настройка Nakamochi занимает всего 5 минут

### Шаг 1: Подключитесь и начните работу

1. Подключите Nakamochi к питанию и Wi-Fi.

2. Нажмите на **"Создать новый кошелек "** и надежно сохраните свою фразу восстановления из 24 слов.

3. Используйте приложение для управления узлами (Zeus или BitBanana) для подключения к вашему Nakamochi:


   - Откройте приложение и отсканируйте QR-код, отображаемый на вашем Nakamochi.

4. Для дополнительной безопасности установите на устройстве PIN-код.

![Connect to power and write down your 24-word seed phrase](assets/en/01.webp)

![Wait until the Blockchain has caught up](assets/en/02.webp)

![Set up new wallet in Lightning Tab](assets/en/03.webp)

![Scan QR Code with Node Management App](assets/en/04.webp)

![For additional safety set a PIN code](asset/en/05.webp)

примечание: Дайте узлу Nakamochi синхронизироваться с блокчейном. Этот процесс может занять некоторое время в зависимости от вашего интернет-соединения._

## О сети Lightning Network

Сеть Bitcoin Lightning Network революционизирует транзакции биткоина, делая их быстрее, дешевле и эффективнее. Она идеально подходит для повседневного использования, обеспечивая практически мгновенные платежи с минимальными комиссиями, что идеально подходит для микротранзакций, таких как покупка кофе, или для частых мелких покупок.

Благодаря автономной работе Lightning может масштабироваться, поддерживая тысячи транзакций в секунду и не перегружая основной блокчейн Биткойна. Это делает его ключевым игроком в эволюции биткойна в практичную глобальную платежную систему.

Еще одним преимуществом является конфиденциальность, поскольку транзакции на Lightning проходят через частные платежные каналы, а не записываются непосредственно в блокчейн. Это обеспечивает более скрытный способ совершения транзакций при сохранении надежной защиты Биткойна.

#### Каналы оплаты: объяснение

Сеть Lightning Network работает через платежные каналы, которые представляют собой соединения между двумя сторонами, позволяющие проводить множество транзакций без непосредственного взаимодействия с блокчейном. Когда канал открыт, баланс между двумя сторонами обновляется на втором уровне решения Lightning для каждой транзакции, обеспечивая быстрые и недорогие платежи. Открытие и закрытие канала фиксируется только на цепочке, что снижает перегрузку блокчейна Bitcoin. Такая конструкция обеспечивает масштабируемость и конфиденциальность, поскольку отдельные транзакции остаются незарегистрированными в публичной бухгалтерской книге.

**Пример:** Алиса и Боб открывают канал, передавая на него биткойны. Алиса отправляет Биткойны Бобу, и их балансы вне цепочки обновляются мгновенно без записи на цепочке. Если Алиса затем заплатит Чарли, а у Алисы нет прямого канала к Чарли, платеж может быть направлен через канал Боба, чтобы достичь Чарли. Маршрутизация через узлы-посредники обеспечивает платежи даже при отсутствии прямого соединения, что делает сеть высокоэффективной.

## Открытие каналов и совершение транзакций в сети Lightning Network

После того как ваш Nakamochi настроен и подключен к приложению для управления узлами, вы можете начать использовать Lightning Network, открывая каналы и совершая транзакции.

### Открытие каналов на Zeus (iOS):

1. Перейдите на вкладку **"Каналы "** (нижнее меню).

2. Нажмите на **"+"**, чтобы открыть новый канал.

3. Отсканируйте или введите pubkey узла, с которым вы хотите установить соединение.

4. Введите сумму блокировки (выберите ее вместе с коллегой или используйте минимальную фиксированную сумму для известных узлов).

5. Нажмите на **"Открыть канал "**.

![ZEUS Screenshot](asset/en/06.webp)

Дополнительная информация: [Каналы | Документация Zeus](https://zeusln.app)

### Открытие каналов на BitBanana (Android):

1. Откройте меню гамбургера (слева).

2. Перейдите в раздел **"Каналы "**.

3. Нажмите на **"+"**, чтобы добавить/открыть новый канал.

4. Отсканируйте или вставьте ключ pubkey.

5. Введите сумму блокировки (выберите ее вместе с коллегой или используйте минимальную фиксированную сумму для известных узлов).

![Bitbanana Screenshot](asset/en/07.webp)

Дополнительная информация: [BitBanana](https://bitbanana.com)

Как только ваш канал открыт, через него можно направлять платежи другим участникам сети. Баланс регулируется вне цепочки, что обеспечивает практически мгновенное проведение транзакций и минимальные комиссии.

Если канал вам больше не нужен, вы можете закрыть его. Это действие позволяет урегулировать окончательный баланс между вами и вашим коллегой и записать его на цепочку. В идеале обе стороны согласны и находятся в сети для "кооперативного закрытия" (быстрее и с меньшими комиссиями по сравнению с "принудительным закрытием" с не реагирующим/офлайновым аналогом).

Как правило, мы рекомендуем оставлять каналы открытыми, чтобы снизить затраты и повысить надежность и эффективность сети. Оставляя каналы открытыми, вы минимизируете комиссию за транзакции на цепи, избегаете простоев при переподключении каналов и поддерживаете стабильную маршрутизацию для бесперебойной обработки платежей. Такой подход способствует созданию надежной и устойчивой сети, повышая общий уровень обслуживания пользователей и снижая операционные издержки.

### Полезные ссылки


- [О Накамоти](https://nakamochi.io/)
- [Подпишитесь на нашу рассылку](https://90c7addc.sibforms.com/serve/MUIFAHG7H5YBPpm-kZ8G6TuS-nmL4uaq85rlpBfI__S79tZ5jheIJfF3kJYudycgs_6_RUdDBkt8Sd7OyNL_JDTTJvOb36ifF6vcQoabBXKp4cbefzh1DYqnok_jItexICcQL13ucd2aS581ngqy7jr0Q1H3HhxV3z2eWKE5-Z-YMasj-MMotQeDvdorMCSi0XgCWDqs8rEMQC7E)