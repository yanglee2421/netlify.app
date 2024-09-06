<script setup lang="ts"></script>

<template>
  <NuxtLayout name="custom">
    <div class="space-y-6 *:border *:p-3 *:shadow">
      <div class="w-full">
        <table
          class="w-full border-collapse border-y border-slate-400 bg-white text-sm shadow-sm dark:border-slate-500 dark:bg-slate-800"
        >
          <thead class="bg-slate-50 dark:bg-slate-700">
            <tr>
              <th
                class="group border border-slate-300 px-4 py-3 text-left font-semibold text-slate-900 first:border-l-0 last:border-r-0 dark:border-slate-600 dark:text-slate-200"
                aria-sort="ascending"
              >
                <span class="flex w-full items-center justify-between gap-2">
                  Invoice #
                  <svg
                    viewBox="0 0 20 20"
                    class="h-5 w-5 fill-slate-500 group-aria-[sort=ascending]:rotate-0 group-aria-[sort=descending]:rotate-180"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 5a.75.75 0 01.75.75v6.638l1.96-2.158a.75.75 0 111.08 1.04l-3.25 3.5a.75.75 0 01-1.08 0l-3.25-3.5a.75.75 0 111.08-1.04l1.96 2.158V5.75A.75.75 0 0110 5z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                </span>
              </th>
              <th
                class="border border-slate-300 px-4 py-3 text-left font-semibold text-slate-900 first:border-l-0 last:border-r-0 dark:border-slate-600 dark:text-slate-200"
              >
                Client
              </th>
              <th
                class="border border-slate-300 px-4 py-3 text-right font-semibold text-slate-900 first:border-l-0 last:border-r-0 dark:border-slate-600 dark:text-slate-200"
              >
                Amount
              </th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td
                class="border border-slate-300 px-4 py-3 text-slate-500 first:border-l-0 last:border-r-0 dark:border-slate-700 dark:text-slate-400"
              >
                #100
              </td>
              <td
                class="border border-slate-300 px-4 py-3 text-slate-500 first:border-l-0 last:border-r-0 dark:border-slate-700 dark:text-slate-400"
              >
                Pendant Publishing
              </td>
              <td
                class="border border-slate-300 px-4 py-3 text-right tabular-nums text-slate-500 first:border-l-0 last:border-r-0 dark:border-slate-700 dark:text-slate-400"
              >
                $2,000.00
              </td>
            </tr>
            <tr>
              <td
                class="border border-slate-300 px-4 py-3 text-slate-500 first:border-l-0 last:border-r-0 dark:border-slate-700 dark:text-slate-400"
              >
                #101
              </td>
              <td
                class="border border-slate-300 px-4 py-3 text-slate-500 first:border-l-0 last:border-r-0 dark:border-slate-700 dark:text-slate-400"
              >
                Kruger Industrial Smoothing
              </td>
              <td
                class="border border-slate-300 px-4 py-3 text-right tabular-nums text-slate-500 first:border-l-0 last:border-r-0 dark:border-slate-700 dark:text-slate-400"
              >
                $545.00
              </td>
            </tr>
            <tr>
              <td
                class="border border-slate-300 px-4 py-3 text-slate-500 first:border-l-0 last:border-r-0 dark:border-slate-700 dark:text-slate-400"
              >
                #102
              </td>
              <td
                class="border border-slate-300 px-4 py-3 text-slate-500 first:border-l-0 last:border-r-0 dark:border-slate-700 dark:text-slate-400"
              >
                J. Peterman
              </td>
              <td
                class="border border-slate-300 px-4 py-3 text-right tabular-nums text-slate-500 first:border-l-0 last:border-r-0 dark:border-slate-700 dark:text-slate-400"
              >
                $10,000.25
              </td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="w-full">
        <table class="min-w-full">
          <thead class="border-b border-slate-200 bg-slate-50">
            <tr>
              <th
                scope="col"
                class="px-6 py-3 text-left text-sm font-medium text-slate-900"
              >
                Name
              </th>
              <th
                scope="col"
                class="px-6 py-3 text-left text-sm font-medium text-slate-900"
              >
                Title
              </th>
              <th
                scope="col"
                class="px-6 py-3 text-left text-sm font-medium text-slate-900"
              >
                Email
              </th>
            </tr>
          </thead>
          <tbody>
            <tr class="odd:bg-white even:bg-slate-50">
              <td
                class="whitespace-nowrap px-6 py-4 text-sm font-medium text-slate-900"
              >
                Jane Cooper
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                Regional Paradigm Technician
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                jane.cooper@example.com
              </td>
            </tr>
            <tr class="odd:bg-white even:bg-slate-50">
              <td
                class="whitespace-nowrap px-6 py-4 text-sm font-medium text-slate-900"
              >
                Cody Fisher
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                Product Directives Officer
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                cody.fisher@example.com
              </td>
            </tr>
            <tr class="odd:bg-white even:bg-slate-50">
              <td
                class="whitespace-nowrap px-6 py-4 text-sm font-medium text-slate-900"
              >
                Leonard Krasner
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                Senior Designer
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                leonard.krasner@example.com
              </td>
            </tr>
            <tr class="odd:bg-white even:bg-slate-50">
              <td
                class="whitespace-nowrap px-6 py-4 text-sm font-medium text-slate-900"
              >
                Emily Selman
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                VP, Hardware Engineering
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                emily.selman@example.com
              </td>
            </tr>
            <tr class="odd:bg-white even:bg-slate-50">
              <td
                class="whitespace-nowrap px-6 py-4 text-sm font-medium text-slate-900"
              >
                Anna Roberts
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                Chief Strategy Officer
              </td>
              <td class="whitespace-nowrap px-6 py-4 text-sm text-slate-600">
                anna.roberts@example.com
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </NuxtLayout>
</template>
