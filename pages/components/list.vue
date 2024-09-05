<script lang="ts" setup></script>

<template>
  <NuxtLayout name="custom">
    <div class="space-y-6">
      <ul role="list" class="max-w-md bg-white p-2 shadow">
        <li
          class="group/item relative flex items-center justify-between rounded-xl p-4 hover:bg-slate-100"
        >
          <div class="flex gap-4">
            <div class="flex-shrink-0">
              <img
                class="h-12 w-12 rounded-full"
                src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
                alt=""
              />
            </div>
            <div class="w-full text-sm leading-6">
              <a href="#" class="font-semibold text-slate-900"
                ><span
                  class="absolute inset-0 rounded-xl"
                  aria-hidden="true"
                ></span
                >Leslie Abbott</a
              >
              <div class="text-slate-500">Co-Founder / CEO</div>
            </div>
          </div>
          <a
            href="#"
            class="group/edit invisible relative flex items-center whitespace-nowrap rounded-full py-1 pl-4 pr-3 text-sm text-slate-500 transition hover:bg-slate-200 group-hover/item:visible"
          >
            <span
              class="font-semibold transition group-hover/edit:text-gray-700"
              >Call</span
            >
            <svg
              class="mt-px h-5 w-5 text-slate-400 transition group-hover/edit:translate-x-0.5 group-hover/edit:text-slate-500"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </a>
        </li>
        <li
          class="group/item relative flex items-center justify-between rounded-xl p-4 hover:bg-slate-100"
        >
          <div class="flex gap-4">
            <div class="flex-shrink-0">
              <img
                class="h-12 w-12 rounded-full"
                src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
                alt=""
              />
            </div>
            <div class="w-full text-sm leading-6">
              <a href="#" class="font-semibold text-slate-900"
                ><span
                  class="absolute inset-0 rounded-xl"
                  aria-hidden="true"
                ></span
                >Hector Adams</a
              >
              <div class="text-slate-500">VP, Marketing</div>
            </div>
          </div>
          <a
            href="#"
            class="group/edit invisible relative flex items-center whitespace-nowrap rounded-full py-1 pl-4 pr-3 text-sm text-slate-500 transition hover:bg-slate-200 group-hover/item:visible"
          >
            <span
              class="font-semibold transition group-hover/edit:text-gray-700"
              >Call</span
            >
            <svg
              class="mt-px h-5 w-5 text-slate-400 transition group-hover/edit:translate-x-0.5 group-hover/edit:text-slate-500"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </a>
        </li>
        <li
          class="group/item relative flex items-center justify-between rounded-xl p-4 hover:bg-slate-100"
        >
          <div class="flex gap-4">
            <div class="flex-shrink-0">
              <img
                class="h-12 w-12 rounded-full"
                src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
                alt=""
              />
            </div>
            <div class="w-full text-sm leading-6">
              <a href="#" class="font-semibold text-slate-900"
                ><span
                  class="absolute inset-0 rounded-xl"
                  aria-hidden="true"
                ></span
                >Blake Alexander</a
              >
              <div class="text-slate-500">Account Coordinator</div>
            </div>
          </div>
          <a
            href="#"
            class="group/edit invisible relative flex items-center whitespace-nowrap rounded-full py-1 pl-4 pr-3 text-sm text-slate-500 transition hover:bg-slate-200 group-hover/item:visible"
          >
            <span
              class="font-semibold transition group-hover/edit:text-gray-700"
              >Call</span
            >
            <svg
              class="mt-px h-5 w-5 text-slate-400 transition group-hover/edit:translate-x-0.5 group-hover/edit:text-slate-500"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </a>
        </li>
      </ul>

      <ul role="list" class="divide-y divide-slate-200 p-6">
        <li class="flex py-4 first:pt-0 last:pb-0">
          <img
            class="h-10 w-10 rounded-full"
            src="https://images.unsplash.com/photo-1550525811-e5869dd03032?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
            alt=""
          />
          <div class="ml-3 overflow-hidden">
            <p class="text-sm font-medium text-slate-900">Kristen Ramos</p>
            <p class="truncate text-sm text-slate-500">
              kristen.ramos@example.com
            </p>
          </div>
        </li>
        <li class="flex py-4 first:pt-0 last:pb-0">
          <img
            class="h-10 w-10 rounded-full"
            src="https://images.unsplash.com/photo-1463453091185-61582044d556?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
            alt=""
          />
          <div class="ml-3 overflow-hidden">
            <p class="text-sm font-medium text-slate-900">Floyd Miles</p>
            <p class="truncate text-sm text-slate-500">
              floyd.miles@example.com
            </p>
          </div>
        </li>
        <li class="flex py-4 first:pt-0 last:pb-0">
          <img
            class="h-10 w-10 rounded-full"
            src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
            alt=""
          />
          <div class="ml-3 overflow-hidden">
            <p class="text-sm font-medium text-slate-900">Courtney Henry</p>
            <p class="truncate text-sm text-slate-500">
              courtney.henry@example.com
            </p>
          </div>
        </li>
        <li class="flex py-4 first:pt-0 last:pb-0">
          <img
            class="h-10 w-10 rounded-full"
            src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
            alt=""
          />
          <div class="ml-3 overflow-hidden">
            <p class="text-sm font-medium text-slate-900">Ted Fox</p>
            <p class="truncate text-sm text-slate-500">ted.fox@example.com</p>
          </div>
        </li>
      </ul>
    </div>
  </NuxtLayout>
</template>

<style lang="scss" scoped></style>
