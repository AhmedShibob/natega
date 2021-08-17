<template>
  <div class="flex items-center justify-center min-h-screen bg-gray-900">
    <div class="w-1/2" style="direction: rtl">
      <div class="overflow-auto lg:overflow-visible">
        <!-- Container -->
        <div class="container mx-auto">
          <div class="flex justify-center px-6 my-12">
            <!-- Row -->
            <div class="w-full flex">
              <div class="w-full bg-white p-5 rounded-lg">
                <h3 class="pt-4 text-2xl text-center">نتيجة الثانوية العامة</h3>
                <form class="px-8 pt-6 pb-8 mb-4 bg-white rounded">
                  <div class="mb-4">
                    <label
                      class="block mb-2 text-sm font-bold text-gray-700"
                      for="email"
                    >
                      اسم الطالب
                    </label>
                    <input
                      class="
                        w-full
                        px-3
                        py-2
                        mb-3
                        text-sm
                        leading-tight
                        text-gray-700
                        h-16
                        border
                        rounded
                        shadow
                        appearance-none
                        focus:outline-none focus:shadow-outline
                      "
                      id="name"
                      type="text"
                      placeholder="مثلا: احمد عمر  يوسف"
                    />
                  </div>

                  <div class="mb-4">
                    <p
                      class="
                        block
                        mb-2
                        text-sm
                        font-bold
                        text-gray-700 text-center
                      "
                    >
                      او
                    </p>
                  </div>

                  <div class="mb-4">
                    <label
                      class="block mb-2 text-sm font-bold text-gray-700"
                      for="email"
                    >
                      رقم الجلوس
                    </label>
                    <input
                      class="
                        w-full
                        px-3
                        py-2
                        mb-3
                        text-sm
                        leading-tight
                        text-gray-700
                        border
                        rounded
                        h-16
                        shadow
                        appearance-none
                        focus:outline-none focus:shadow-outline
                      "
                      autocomplete="off"
                      id="seating_no"
                      type="number"
                      placeholder="رقم الجلوس"
                    />
                  </div>

                  <div class="mb-6 text-center">
                    <button
                      class="
                        w-full
                        px-4
                        py-2
                        font-bold
                        text-white
                        bg-blue-500
                        rounded-full
                        hover:bg-blue-700
                        focus:outline-none focus:shadow-outline
                      "
                      type="button"
                    >
                      النتيجة
                    </button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.table {
  border-spacing: 0 15px;
}

i {
  font-size: 1rem !important;
}

.table tr {
  border-radius: 20px;
}

tr td:nth-child(n + 5),
tr th:nth-child(n + 5) {
  border-radius: 0 0.625rem 0.625rem 0;
}

tr td:nth-child(1),
tr th:nth-child(1) {
  border-radius: 0.625rem 0 0 0.625rem;
}
</style>
