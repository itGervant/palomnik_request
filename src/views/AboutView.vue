<template>
  <div class="request">
    <div>
      <h1><strong>Заявка №420</strong></h1>
    </div>
    <div class="wrapper">
      <select
        class="form-select"
        aria-label="Пример выбора по умолчанию"
        style="margin-left: 15px"
      >
        <option selected>Программы</option>
        <option value="1">Расписание</option>
        <option value="2">Однодневные</option>
        <option value="3">Многодневные</option>
        <option value="4">Индивидуальные</option>
        <option value="5">Приходам</option>
        <option value="6">Организованным группам</option>
        <option value="7">Услуги</option>
        <option value="8">Отправить заявку</option>
      </select>
      <select class="form-select" aria-label="Пример выбора по умолчанию">
        <option selected>На Валааме</option>
        <option value="1">Экскурсии</option>
        <option value="2">Размещение</option>
        <option value="3">Теплоходы</option>
        <option value="4">Правила поведения в монастыре</option>
      </select>
      <select class="form-select" aria-label="Пример выбора по умолчанию">
        <option selected>Информация</option>
        <option value="1">Условия оплаты</option>
        <option value="2">Реквизиты</option>
        <option value="3">Возврат денежных средств</option>
        <option value="4">Обучение экскурсоводов</option>
        <option value="5">Волонтером на Валаам</option>
        <option value="6">Часто задаваемые вопросы</option>
      </select>
      <select class="form-select" aria-label="Пример выбора по умолчанию">
        <option selected>О нас</option>
        <option value="1">Паломническая служба</option>
        <option value="2">Статьи</option>
        <option value="3">Новости</option>
        <option value="4">Подписка</option>
        <option value="5">Вакансии</option>
        <option value="6">Отзывы</option>
        <option value="7">Контакты</option>
      </select>
      <select class="form-select" aria-label="Пример выбора по умолчанию">
        <option selected>Заказ</option>
      </select>
    </div>

    <div class="wrapper">
      <div class="card" style="width: 100%">
        <div class="card-body" style="padding: 0">
          <div class="card-table table-responsive">
            <h3 class="card-header">Валаамское мгновение из Приозерска</h3>
            <table class="table">
              <thead></thead>
              <tbody>
                <tr>
                  <td class="align-middle">Автобус</td>
                  <td class="align-middle">28.07.23 8:00</td>
                  <td class="align-middle">Санкт-Петербург</td>
                  <td class="align-middle">-</td>
                  <td class="align-middle">причал</td>
                  <td class="align-middle">№ автобуса</td>
                  <td class="align-middle">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                      style="width: 50px"
                    />
                  </td>
                  <td class="align-middle">№ рейса</td>
                  <td class="align-middle">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                      style="width: 50px"
                    />
                  </td>
                  <td class="align-middle">
                    <button type="button" class="btn">
                      <img src="../assets/edit.svg" />
                    </button>
                  </td>
                </tr>
                <tr>
                  <td class="align-middle">Автобус</td>
                  <td class="align-middle">30.07.23 14:00</td>
                  <td class="align-middle">причал</td>
                  <td class="align-middle">-</td>
                  <td class="align-middle">Санкт-Петербург</td>
                  <td class="align-middle">№ автобуса</td>
                  <td class="align-middle">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                      style="width: 50px"
                    />
                  </td>
                  <td class="align-middle">№ рейса</td>
                  <td class="align-middle">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                      style="width: 50px"
                    />
                  </td>
                  <td class="align-middle">
                    <button type="button" class="btn">
                      <img src="../assets/edit.svg" />
                    </button>
                  </td>
                </tr>
                <tr>
                  <td class="align-middle">Сопровождающий</td>
                  <td class="align-middle">Попова</td>
                  <td class="align-middle">Евгения</td>
                  <td class="align-middle">Викторовна</td>
                  <td class="align-middle">телефон</td>
                  <td class="align-middle">89012345678</td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle">
                    <button type="button" class="btn">
                      <img src="../assets/edit.svg" />
                    </button>
                  </td>
                </tr>
                <tr>
                  <td class="align-middle">Рейс туда</td>
                  <td class="align-middle">28.07.23</td>
                  <td class="align-middle">Приозерск</td>
                  <td class="align-middle">></td>
                  <td class="align-middle">Валаам</td>
                  <td class="align-middle">11:00</td>
                  <td class="align-middle">метеор</td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle">
                    <button type="button" class="btn">
                      <img src="../assets/edit.svg" />
                    </button>
                  </td>
                </tr>
                <tr>
                  <td class="align-middle">Рейс обратно</td>
                  <td class="align-middle">30.07.23</td>
                  <td class="align-middle">Валаам</td>
                  <td class="align-middle">></td>
                  <td class="align-middle">Приозерск</td>
                  <td class="align-middle">12:00</td>
                  <td class="align-middle">метеор</td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle">
                    <button type="button" class="btn">
                      <img src="../assets/edit.svg" />
                    </button>
                  </td>
                </tr>
                <tr>
                  <td class="align-middle">Размещение</td>
                  <td class="align-middle">Дом паломника "Валаам"</td>
                  <td class="align-middle">Стандартные номера</td>
                  <td class="align-middle">1 номер</td>
                  <td class="align-middle">28.07.23</td>
                  <td class="align-middle">-</td>
                  <td class="align-middle">30.07.23</td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle">
                    <button type="button" class="btn">
                      <img src="../assets/edit.svg" />
                    </button>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>

    <div class="wrapper">
      <div class="card">
        <div class="card-body" style="padding: 0">
          <div class="card-table table-responsive">
            <h3 class="card-header">Питание</h3>
            <table class="table table-sm">
              <tbody>
                <tr style="display: flex; align-items: baseline">
                  <td class="text-muted">
                    <p class="text-muted">Завтраков</p>
                  </td>
                  <td class="text-muted">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                      style="width: 50px"
                    />
                  </td>
                  <td class="text-muted">
                    <div class="mb-3">
                      <div class="form-label"></div>
                      <select class="form-select">
                        <option value="1">Стандартное</option>
                        <option value="2">Постное</option>
                        <option value="3">Детское</option>
                      </select>
                    </div>
                  </td>
                  <td class="text-muted">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon icon-tabler icon-tabler-circle-letter-x"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <circle cx="12" cy="12" r="9"></circle>
                      <path d="M10 8l4 8"></path>
                      <path d="M10 16l4 -8"></path>
                    </svg>
                  </td>
                </tr>
                <tr
                  style="
                    display: flex;
                    align-items: baseline;
                    border-bottom: none;
                    margin-bottom: 0px;
                  "
                >
                  <td class="text-muted">
                    <p class="text-muted">Обедов</p>
                  </td>
                  <td class="text-muted">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                      style="width: 50px"
                    />
                  </td>
                  <td class="text-muted">
                    <div class="mb-3">
                      <div class="form-label"></div>
                      <select class="form-select">
                        <option value="1">Стандартное</option>
                        <option value="2">Постное</option>
                        <option value="3">Детское</option>
                      </select>
                    </div>
                  </td>
                  <td class="text-muted">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon icon-tabler icon-tabler-circle-letter-x"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <circle cx="12" cy="12" r="9"></circle>
                      <path d="M10 8l4 8"></path>
                      <path d="M10 16l4 -8"></path>
                    </svg>
                  </td>
                </tr>
                <tr
                  style="
                    display: flex;
                    align-items: baseline;
                    border-bottom: none;
                    margin-bottom: 0px;
                  "
                >
                  <td class="text-muted">
                    <p class="text-muted">Завтраков</p>
                  </td>
                  <td class="text-muted">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                      style="width: 50px"
                    />
                  </td>
                  <td class="text-muted">
                    <div class="mb-3">
                      <div class="form-label"></div>
                      <select class="form-select">
                        <option value="1">Стандартное</option>
                        <option value="2">Постное</option>
                        <option value="3">Детское</option>
                      </select>
                    </div>
                  </td>
                  <td class="text-muted">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon icon-tabler icon-tabler-circle-letter-x"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <circle cx="12" cy="12" r="9"></circle>
                      <path d="M10 8l4 8"></path>
                      <path d="M10 16l4 -8"></path>
                    </svg>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-body" style="padding: 0">
          <div class="card-table table-responsive">
            <h3 class="card-header">Экскурсии,услуги</h3>
            <table class="table table-sm">
              <tbody>
                <tr>
                  <td class="align-middle">
                    <a href="#">Никольский скит</a>
                  </td>
                  <td class="align-middle">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon icon-tabler icon-tabler-circle-letter-x"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <circle cx="12" cy="12" r="9"></circle>
                      <path d="M10 8l4 8"></path>
                      <path d="M10 16l4 -8"></path>
                    </svg>
                  </td>
                </tr>
                <tr>
                  <td class="align-middle">
                    <a href="#">Скиты Всех Святых и Смоленский</a>
                  </td>
                  <td class="align-middle">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon icon-tabler icon-tabler-circle-letter-x"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <circle cx="12" cy="12" r="9"></circle>
                      <path d="M10 8l4 8"></path>
                      <path d="M10 16l4 -8"></path>
                    </svg>
                  </td>
                </tr>
              </tbody>
            </table>
            <p class="text-end">
              <a href="#" class="btn btn-primary" style="margin: 5px">
                Добавить
              </a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="wrapper">
    <div class="card" style="width: 100%">
      <div class="card-table table-responsive">
        <h3 class="card-header">Данные туристов</h3>
        <table class="table">
          <thead></thead>
          <tbody>
            <tr>
              <td class="text-muted">Фамилия</td>
              <td class="text-muted">Имя</td>
              <td class="text-muted">Отчество</td>
              <td class="text-muted">Дата рождения</td>
              <td class="text-muted">Паспорт серия номер*</td>
              <td class="text-muted">Телефон</td>
              <td class="text-muted">Статус</td>
              <td class="text-muted">Пол</td>
            </tr>
            <tr>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <div class="mb-3">
                  <select class="form-select">
                    <option value="1">Взрослый</option>
                    <option value="2">ребенок до 12 лет</option>
                    <option value="3">ребенок до 6 лет</option>
                    <option value="4">пенсионер</option>
                  </select>
                </div>
              </td>
              <td class="text-muted">
                <div class="mb-3">
                  <select class="form-select">
                    <option value="1">мужской</option>
                    <option value="2">женский</option>
                  </select>
                </div>
              </td>
            </tr>
            <tr>
              <td class="text-muted">Фамилия</td>
              <td class="text-muted">Имя</td>
              <td class="text-muted">Отчество</td>
              <td class="text-muted">Дата рождения</td>
              <td class="text-muted">Паспорт серия номер*</td>
              <td class="text-muted">Телефон</td>
              <td class="text-muted">Статус</td>
              <td class="text-muted">Пол</td>
            </tr>
            <tr>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <input
                  type="text"
                  class="form-control"
                  name="example-text-input"
                />
              </td>
              <td class="text-muted">
                <div class="mb-3">
                  <select class="form-select">
                    <option value="1">Взрослый</option>
                    <option value="2">ребенок до 12 лет</option>
                    <option value="3">ребенок до 6 лет</option>
                    <option value="4">пенсионер</option>
                  </select>
                </div>
              </td>
              <td class="text-muted">
                <div class="mb-3">
                  <select class="form-select">
                    <option value="1">мужской</option>
                    <option value="2">женский</option>
                  </select>
                </div>
              </td>
            </tr>
          </tbody>
        </table>
        <p class="text-end">
          <a href="#" class="btn btn-primary" style="margin: 5px 25px 5px 5px">
            Добавить
          </a>
        </p>
      </div>
    </div>
  </div>

  <div class="wrapper">
    <div class="card">
      <div class="card-table table-responsive">
        <h3 class="card-header">Файлы к заявке</h3>
        <div
          style="
            display: flex;
            align-items: center;
            justify-content: space-between;
          "
        >
          <div class="align-middle">
            <a href="#" style="margin: 5px">Билет</a>
          </div>
          <div
            style="
              display: flex;
              flex-direction: column;
              align-items: center;
              margin: 5px;
            "
          >
            <a href="#" class="btn" role="button">Загрузить</a>
            <a href="#" class="btn" role="button" style="width: 100%"
              >Удалить</a
            >
          </div>
        </div>
      </div>
    </div>
    <div class="card">
      <div class="card-body">
        <h3 class="card-title">Взаимоотношения по заявке</h3>
        <div class="card-table table-responsive" style="display: flex">
          <table class="table" style="width: 50%">
            <thead>
              <tr>
                <th>Операция</th>
                <th>Дата</th>
                <th>Сумма + -</th>
                <th>Итог</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="text-muted"></td>
                <td class="text-muted"></td>
                <td class="text-muted"></td>
                <td class="text-muted"></td>
              </tr>
              <tr>
                <td class="text-muted"></td>
                <td class="text-muted"></td>
                <td class="text-muted"></td>
                <td class="text-muted"></td>
              </tr>
            </tbody>
          </table>
          <div style="display: flex; flex-direction: column; margin-left: 50px">
            <svg
              version="1.1"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              width="102px"
              height="90px"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g transform="matrix(1 0 0 1 -947 -1562 )">
                <path
                  d="M 18.545454545454547 65.45454545454545  L 27.818181818181817 65.45454545454545  L 27.818181818181817 73.63636363636363  L 18.545454545454547 73.63636363636363  L 18.545454545454547 65.45454545454545  Z M 18.545454545454547 16.36363636363636  L 27.818181818181817 16.36363636363636  L 27.818181818181817 24.545454545454543  L 18.545454545454547 24.545454545454543  L 18.545454545454547 16.36363636363636  Z M 74.18181818181819 16.36363636363636  L 83.45454545454545 16.36363636363636  L 83.45454545454545 24.545454545454543  L 74.18181818181819 24.545454545454543  L 74.18181818181819 16.36363636363636  Z M 10 57  L 10 81  L 37 81  L 37 57  L 10 57  Z M 10 9  L 10 33  L 37 33  L 37 9  L 10 9  Z M 65 9  L 65 33  L 92 33  L 92 9  L 65 9  Z M 0 49  L 47 49  L 47 90  L 0 90  L 0 49  Z M 74.18181818181819 81.81818181818181  L 83.45454545454545 81.81818181818181  L 83.45454545454545 90  L 74.18181818181819 90  L 74.18181818181819 81.81818181818181  Z M 92.72727272727272 81.81818181818181  L 102 81.81818181818181  L 102 90  L 92.72727272727272 90  L 92.72727272727272 81.81818181818181  Z M 92.72727272727272 49.090909090909086  L 102 49.090909090909086  L 102 73  L 74.18181818181819 73  L 74.18181818181819 65.45454545454545  L 65 65.45454545454545  L 65 90  L 55 90  L 55 49  L 83.45454545454545 49  L 83.45454545454545 57.27272727272727  L 92.72727272727272 57.27272727272727  L 92.72727272727272 49.090909090909086  Z M 0 0  L 47 0  L 47 41  L 0 41  L 0 0  Z M 55 0  L 102 0  L 102 41  L 55 41  L 55 0  Z "
                  fill-rule="nonzero"
                  fill="#000000"
                  stroke="none"
                  transform="matrix(1 0 0 1 947 1562 )"
                />
              </g>
            </svg>
            <a href="#" class="btn" role="button" style="margin-top: 10px"
              >Скачать</a
            >
          </div>
        </div>
      </div>
    </div>
    <div class="card">
      <div class="card-table table-responsive">
        <h3 class="card-header">Документы для скачивания</h3>
        <div
          style="
            display: flex;
            align-items: center;
            justify-content: space-between;
          "
        >
          <div class="align-middle">
            <a href="#" style="margin: 5px">Билет</a>
          </div>
        </div>
        <div>
          <div class="mb-3">
            <div class="form-label"></div>
            <select class="form-select">
              <option value="1">1.Резерв (закрыто к продаже)</option>
              <option value="2">2.Свободно (открыто к продаже)</option>
              <option value="3">3.Бронь (закрыто к продаже)</option>
              <option value="4">4.Продано (закрыто к продаже)</option>
            </select>
          </div>
        </div>
        <div style="display: flex; justify-content: space-between">
          <p class="text-end">
            <a href="#" class="btn btn-primary"> Сохранить </a>
          </p>
          <p class="text-end">
            <a href="#" class="btn btn-danger"> Отменить </a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.eats {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.text-muted {
  border: none;
}

.wrapper {
  display: flex;
  margin: 15px;
}
.card {
  margin-left: 15px;
}
</style>