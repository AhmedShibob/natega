<template>
  <div>
    <div
      class="flex flex-col items-center justify-center min-h-screen bg-gray-900"
    >
      <div class="w-full" style="direction: rtl">
        <div class="overflow-auto lg:overflow-visible">
          <!-- Container -->
          <div class="container mx-auto">
            <div class="flex justify-center px-6 my-12">
              <!-- Row -->
              <div class="w-full flex">
                <div class="w-full bg-white rounded-lg">
                  <div class="bg-white overflow-hidden sm:rounded-lg">
                    <div class="px-4 py-5 sm:px-6">
                      <div class="flex flex-col">
                        <div class="-my-2 overflow-x-auto sm:-mx-6 lg:-mx-8">
                          <div
                            class="
                              py-2
                              align-middle
                              inline-block
                              min-w-full
                              sm:px-6
                              lg:px-8
                            "
                          >
                            <div
                              class="
                                shadow
                                overflow-hidden
                                border-b border-gray-200
                                sm:rounded-lg
                              "
                            >
                              <table
                                class="min-w-full divide-y divide-gray-200"
                              >
                                <thead class="bg-gray-50">
                                  <tr>
                                    <th
                                      scope="col"
                                      class="
                                        px-6
                                        py-3
                                        text-right text-xs
                                        font-medium
                                        text-gray-500
                                        uppercase
                                        tracking-wider
                                      "
                                    >
                                      اسم الطالب
                                    </th>
                                    <th
                                      scope="col"
                                      class="
                                        px-6
                                        py-3
                                        text-right text-xs
                                        font-medium
                                        text-gray-500
                                        uppercase
                                        tracking-wider
                                      "
                                    >
                                      اسم المدرسة
                                    </th>
                                    <th
                                      scope="col"
                                      class="
                                        px-6
                                        py-3
                                        text-right text-xs
                                        font-medium
                                        text-gray-500
                                        uppercase
                                        tracking-wider
                                      "
                                    >
                                      اسم الادارة
                                    </th>
                                    <th
                                      scope="col"
                                      class="
                                        px-6
                                        py-3
                                        text-right text-xs
                                        font-medium
                                        text-gray-500
                                        uppercase
                                        tracking-wider
                                      "
                                    >
                                      النتيجة
                                    </th>
                                    <th scope="col" class="relative px-6 py-3">
                                      <span class="sr-only">عرض النتيجة</span>
                                    </th>
                                  </tr>
                                </thead>
                                <tbody
                                  class="bg-white divide-y divide-gray-200"
                                >
                                  <tr
                                    v-for="person in people"
                                    :key="person.email"
                                  >
                                    <td
                                      class="
                                        px-6
                                        py-4
                                        whitespace-nowrap
                                        text-sm text-gray-500
                                      "
                                    >
                                      احمد يوسف عمر
                                    </td>

                                    <td
                                      class="
                                        px-6
                                        py-4
                                        whitespace-nowrap
                                        text-sm text-gray-500
                                      "
                                    >
                                      الفاروق عمر بن الخطاب
                                    </td>

                                    <td
                                      class="
                                        px-6
                                        py-4
                                        whitespace-nowrap
                                        text-sm text-gray-500
                                      "
                                    >
                                      نجع حمادي
                                    </td>

                                    <td
                                      class="
                                        px-6
                                        py-4
                                        whitespace-nowrap
                                        text-sm text-gray-500
                                      "
                                    >
                                      ناجح
                                    </td>
                                    <td
                                      class="
                                        px-6
                                        py-4
                                        whitespace-nowrap
                                        text-right text-sm
                                        font-medium
                                      "
                                    >
                                      <nuxt-link
                                        to="/natega"
                                        class="
                                          text-indigo-600
                                          hover:text-indigo-900
                                        "
                                      >
                                        عرض النتيجه
                                      </nuxt-link>
                                    </td>
                                  </tr>
                                </tbody>
                              </table>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      people: [
        {
          name: 'Jane Cooper',
          title: 'Regional Paradigm Technician',
          department: 'Optimization',
          role: 'Admin',
          email: 'jane.cooper@example.com',
          image:
            'https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=256&h=256&q=60',
        },
        {
          name: 'Jane Cooper',
          title: 'Regional Paradigm Technician',
          department: 'Optimization',
          role: 'Admin',
          email: 'jane.cooper@example.com',
          image:
            'https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=256&h=256&q=60',
        },
        {
          name: 'Jane Cooper',
          title: 'Regional Paradigm Technician',
          department: 'Optimization',
          role: 'Admin',
          email: 'jane.cooper@example.com',
          image:
            'https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=256&h=256&q=60',
        },
        {
          name: 'Jane Cooper',
          title: 'Regional Paradigm Technician',
          department: 'Optimization',
          role: 'Admin',
          email: 'jane.cooper@example.com',
          image:
            'https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=256&h=256&q=60',
        },
        {
          name: 'Jane Cooper',
          title: 'Regional Paradigm Technician',
          department: 'Optimization',
          role: 'Admin',
          email: 'jane.cooper@example.com',
          image:
            'https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=256&h=256&q=60',
        },
        // More people...
      ],
    }
  },
}
</script>
