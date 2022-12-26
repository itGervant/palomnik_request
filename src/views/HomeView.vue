<template>
  <div class="requests">
    <h1>Заявки</h1>
    <div class="wrapper">
      <div class="card" style="width: 100%">
        <div class="card-body" style="padding: 0">
          <div class="card-table table-responsive">
            <table class="table">
              <thead></thead>
              <tbody>
                <tr>
                  <td class="align-middle">Фильтр</td>
                  <td class="align-middle">Период</td>
                  <td class="align-middle"></td>
                  <td class="align-middle">ФИО</td>
                  <td class="align-middle">Телефон</td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                </tr>
                <tr>
                  <td class="align-middle">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon icon-tabler icon-tabler-filter"
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
                      <path
                        d="M5.5 5h13a1 1 0 0 1 .5 1.5l-5 5.5l0 7l-4 -3l0 -4l-5 -5.5a1 1 0 0 1 .5 -1.5"
                      ></path>
                    </svg>
                  </td>
                  <td class="align-middle">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                    />
                  </td>
                  <td class="align-middle">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon icon-tabler icon-tabler-calendar-due"
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
                      <rect x="4" y="5" width="16" height="16" rx="2"></rect>
                      <path d="M16 3v4"></path>
                      <path d="M8 3v4"></path>
                      <path d="M4 11h16"></path>
                      <circle cx="12" cy="16" r="1"></circle>
                    </svg>
                  </td>
                  <td class="align-middle">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                    />
                  </td>
                  <td class="align-middle">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                    />
                  </td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle">
                    <div class="mb-3" style="width: 150px">
                      <div class="form-label"></div>
                      <select class="form-select">
                        <option value="1">Агент 1</option>
                        <option value="2">Агент 2</option>
                      </select>
                    </div>
                  </td>
                  <td class="align-middle">
                    <a href="#" class="btn btn-primary" style="margin: 5px">
                      Найти
                    </a>
                  </td>
                  <td class="align-middle"></td>
                </tr>
                <tr>
                  <td class="align-middle"></td>
                  <td class="align-middle">
                    <input
                      type="text"
                      class="form-control"
                      name="example-text-input"
                    />
                  </td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle"></td>
                  <td class="align-middle">
                    <div class="mb-3">
                      <div class="form-label"></div>
                      <select class="form-select">
                        <option value="1">Менеджер 1</option>
                        <option value="2">Менеджер 2</option>
                      </select>
                    </div>
                  </td>
                  <td class="align-middle">
                    <a href="#" class="btn btn-primary" style="margin: 5px">
                      Найти
                    </a>
                  </td>
                  <td class="align-middle"></td>
                </tr>
              </tbody>
            </table>
            <div class="table-responsive">
              <table class="table table-vcenter">
                <thead>
                  <tr>
                    <th>id</th>
                    <th>Дата</th>
                    <th>Время</th>
                    <th>ФИО заказчика</th>
                    <th>Программа</th>
                    <th>Тел.заказчика</th>
                    <th>Человек</th>
                    <th>Сумма</th>
                    <th>% оплаты</th>
                    <th>Агент</th>
                    <th>Менеджер</th>
                    <th>Статус заявки</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted">
                      <div class="mb-3">
                        <div class="form-label"></div>
                        <select class="form-select">
                          <option value="1">
                            1.Резерв (закрыто к продаже)
                          </option>
                          <option value="2">
                            2.Свободно (открыто к продаже)
                          </option>
                          <option value="3">3.Бронь (закрыто к продаже)</option>
                          <option value="4">
                            4.Продано (закрыто к продаже)
                          </option>
                        </select>
                      </div>
                    </td>
                  </tr>
                  <tr>
                    <td></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted"></td>
                    <td class="text-muted">
                      <div class="mb-3">
                        <div class="form-label"></div>
                        <select class="form-select">
                          <option value="1">
                            1.Резерв (закрыто к продаже)
                          </option>
                          <option value="2">
                            2.Свободно (открыто к продаже)
                          </option>
                          <option value="3">3.Бронь (закрыто к продаже)</option>
                          <option value="4">
                            4.Продано (закрыто к продаже)
                          </option>
                        </select>
                      </div>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
            <div class="card-body" style="margin-top: 5px">
              <ul class="pagination">
                <li class="page-item disabled">
                  <a
                    class="page-link"
                    href="#"
                    tabindex="-1"
                    aria-disabled="true"
                  >
                    <!-- Download SVG icon from http://tabler-icons.io/i/chevron-left -->
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon"
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
                      <polyline points="15 6 9 12 15 18"></polyline>
                    </svg>
                  </a>
                </li>
                <li class="page-item"><a class="page-link" href="#">1</a></li>
                <li class="page-item"><a class="page-link" href="#">2</a></li>
                <li class="page-item"><a class="page-link" href="#">3</a></li>
                <li class="page-item"><a class="page-link" href="#">...</a></li>
                <li class="page-item"><a class="page-link" href="#">25</a></li>
                <li class="page-item">
                  <a class="page-link" href="#">
                    <!-- Download SVG icon from http://tabler-icons.io/i/chevron-right -->
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon"
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
                      <polyline points="9 6 15 12 9 18"></polyline>
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
