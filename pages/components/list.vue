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

      <div class="max-w-sm bg-white px-8 py-8 shadow dark:bg-slate-800">
        <h2 class="text-base font-semibold text-slate-900 dark:text-slate-200">
          Ingredients
        </h2>
        <ul
          role="list"
          class="mt-3 list-disc space-y-3 pl-5 text-slate-500 marker:text-sky-400 dark:text-slate-400"
        >
          <li>5 cups chopped Porcini mushrooms</li>
          <li>1/2 cup of olive oil</li>
          <li>3lb of celery</li>
        </ul>
      </div>

      <div
        class="grid max-w-md divide-y divide-slate-100 bg-white text-slate-700 shadow"
      >
        <div
          class="group grid grid-cols-[32px_1fr_auto] items-center gap-x-4 px-4 py-4 pt-6"
        >
          <img
            class="size-[32px] rounded-full"
            src="https://spotlight.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Favatar.51a13c67.jpg&amp;w=128&amp;q=80"
            alt=""
          />
          <h4 class="font-semibold text-slate-900">Spencer Sharp</h4>
          <svg
            fill="none"
            viewBox="0 0 24 24"
            strokewidth="1.5"
            stroke="currentColor"
            class="hidden size-4 group-has-[a]:block"
          >
            <path
              strokelinecap="round"
              strokelinejoin="round"
              d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25"
            ></path>
          </svg>
          <p class="col-start-2 text-sm">
            Product Designer at
            <a href="#" class="text-blue-500 underline">planeteria.tech</a>
          </p>
        </div>
        <div
          class="group grid grid-cols-[32px_1fr_auto] items-center gap-x-4 px-4 py-4"
        >
          <img
            class="size-[32px] rounded-full"
            src="https://images.unsplash.com/photo-1539571696357-5a69c17a67c6?q=80&amp;w=256&amp;h=256&amp;auto=format&amp;fit=crop&amp;ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt=""
          />
          <h4 class="font-semibold text-slate-900">Casey Jordan</h4>
          <svg
            fill="none"
            viewBox="0 0 24 24"
            strokewidth="1.5"
            stroke="currentColor"
            class="hidden size-4 group-has-[a]:block"
          >
            <path
              strokelinecap="round"
              strokelinejoin="round"
              d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25"
            ></path>
          </svg>
          <p class="col-start-2 text-sm">Just happy to be here.</p>
        </div>
        <div
          class="group grid grid-cols-[32px_1fr_auto] items-center gap-x-4 px-4 py-4"
        >
          <img
            class="size-[32px] rounded-full"
            src="https://images.unsplash.com/photo-1590895340509-793cb98788c9?q=80&amp;w=256&amp;h=256&amp;&amp;auto=format&amp;fit=crop&amp;ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt=""
          />
          <h4 class="font-semibold text-slate-900">Alex Reed</h4>
          <svg
            fill="none"
            viewBox="0 0 24 24"
            strokewidth="1.5"
            stroke="currentColor"
            class="hidden size-4 group-has-[a]:block"
          >
            <path
              strokelinecap="round"
              strokelinejoin="round"
              d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25"
            ></path>
          </svg>
          <p class="col-start-2 text-sm">
            A multidisciplinary designer, working at the intersection of art and
            technology.<br /><a href="#" class="text-blue-500 underline"
              >alex-reed.com</a
            >
          </p>
        </div>
        <div
          class="group grid grid-cols-[32px_1fr_auto] items-center gap-x-4 px-4 py-4 pb-6"
        >
          <img
            class="size-[32px] rounded-full"
            src="https://images.unsplash.com/photo-1517841905240-472988babdf9?q=80&amp;w=256&amp;h=256&amp;auto=format&amp;fit=crop&amp;ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt=""
          />
          <h4 class="font-semibold text-slate-900">Taylor Bailey</h4>
          <svg
            fill="none"
            viewBox="0 0 24 24"
            strokewidth="1.5"
            stroke="currentColor"
            class="hidden size-4 group-has-[a]:block"
          >
            <path
              strokelinecap="round"
              strokelinejoin="round"
              d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25"
            ></path>
          </svg>
          <p class="col-start-2 text-sm">Pushing pixels. Slinging divs.</p>
        </div>
      </div>
    </div>
  </NuxtLayout>
</template>

<style lang="scss" scoped></style>
