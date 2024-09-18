<template>
  <NuxtLayout name="custom">
    <div class="space-y-6">
      <div
        class="flex max-w-sm items-center space-x-4 rounded-xl bg-white p-6 shadow-lg"
      >
        <div class="shrink-0">
          <svg
            class="h-12 w-12"
            viewBox="0 0 40 40"
            xmlns="http://www.w3.org/2000/svg"
          >
            <defs>
              <linearGradient id="a" x1="50%" y1="0%" x2="50%" y2="100%">
                <stop stop-color="#2397B3" offset="0%"></stop>
                <stop stop-color="#13577E" offset="100%"></stop>
              </linearGradient>
              <linearGradient id="b" x1="50%" y1="0%" x2="50%" y2="100%">
                <stop stop-color="#73DFF2" offset="0%"></stop>
                <stop stop-color="#47B1EB" offset="100%"></stop>
              </linearGradient>
            </defs>
            <g fill="none" fill-rule="evenodd">
              <path
                d="M28.872 22.096c.084.622.128 1.258.128 1.904 0 7.732-6.268 14-14 14-2.176 0-4.236-.496-6.073-1.382l-6.022 2.007c-1.564.521-3.051-.966-2.53-2.53l2.007-6.022A13.944 13.944 0 0 1 1 24c0-7.331 5.635-13.346 12.81-13.95A9.967 9.967 0 0 0 13 14c0 5.523 4.477 10 10 10a9.955 9.955 0 0 0 5.872-1.904z"
                fill="url(#a)"
                transform="translate(1 1)"
              ></path>
              <path
                d="M35.618 20.073l2.007 6.022c.521 1.564-.966 3.051-2.53 2.53l-6.022-2.007A13.944 13.944 0 0 1 23 28c-7.732 0-14-6.268-14-14S15.268 0 23 0s14 6.268 14 14c0 2.176-.496 4.236-1.382 6.073z"
                fill="url(#b)"
                transform="translate(1 1)"
              ></path>
              <path
                d="M18 17a2 2 0 1 0 0-4 2 2 0 0 0 0 4zM24 17a2 2 0 1 0 0-4 2 2 0 0 0 0 4zM30 17a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"
                fill="#FFF"
              ></path>
            </g>
          </svg>
        </div>
        <div>
          <div class="text-xl font-medium text-black">ChitChat</div>
          <p class="text-slate-500">You have a new message!</p>
        </div>
      </div>

      <div class="max-w-sm bg-white px-6 pb-4 pt-6 shadow">
        <form>
          <legend>Choose a theme:</legend>
          <div class="mt-4 grid grid-flow-col">
            <label for="theme-1" class="text-sm font-medium text-slate-700">
              <div
                class="relative grid h-16 w-16 items-center justify-center rounded-xl border border-transparent bg-transparent text-white hover:bg-slate-50 has-[:checked]:border-cyan-500 has-[:checked]:bg-cyan-50 has-[:checked]:text-cyan-50 forced-colors:border-0"
              >
                <input
                  id="theme-1"
                  type="radio"
                  name="themes"
                  class="appearance-none forced-colors:appearance-auto"
                  checked
                />
                <p class="hidden forced-colors:block">Cyan</p>
                <div
                  class="absolute left-3 top-3 h-6 w-6 rounded-full bg-cyan-200 forced-colors:hidden"
                ></div>
                <div
                  class="absolute bottom-3 right-3 h-6 w-6 rounded-full bg-cyan-500 ring-2 ring-current forced-colors:hidden"
                ></div>
              </div>
            </label>
            <label for="theme-2" class="text-sm font-medium text-slate-700">
              <div
                class="relative grid h-16 w-16 items-center justify-center rounded-xl border border-transparent bg-transparent text-white hover:bg-slate-50 has-[:checked]:border-blue-500 has-[:checked]:bg-blue-50 has-[:checked]:text-blue-50 forced-colors:border-0"
              >
                <input
                  id="theme-2"
                  type="radio"
                  name="themes"
                  class="appearance-none forced-colors:appearance-auto"
                />
                <p class="hidden forced-colors:block">Blue</p>
                <div
                  class="absolute left-3 top-3 h-6 w-6 rounded-full bg-blue-200 forced-colors:hidden"
                ></div>
                <div
                  class="absolute bottom-3 right-3 h-6 w-6 rounded-full bg-blue-500 ring-2 ring-current forced-colors:hidden"
                ></div>
              </div>
            </label>
            <label for="theme-3" class="text-sm font-medium text-slate-700">
              <div
                class="relative grid h-16 w-16 items-center justify-center rounded-xl border border-transparent bg-transparent text-white hover:bg-slate-50 has-[:checked]:border-indigo-500 has-[:checked]:bg-indigo-50 has-[:checked]:text-indigo-50 forced-colors:border-0"
              >
                <input
                  id="theme-3"
                  type="radio"
                  name="themes"
                  class="appearance-none forced-colors:appearance-auto"
                />
                <p class="hidden forced-colors:block">Indigo</p>
                <div
                  class="absolute left-3 top-3 h-6 w-6 rounded-full bg-indigo-200 forced-colors:hidden"
                ></div>
                <div
                  class="absolute bottom-3 right-3 h-6 w-6 rounded-full bg-indigo-500 ring-2 ring-current forced-colors:hidden"
                ></div>
              </div>
            </label>
            <label for="theme-4" class="text-sm font-medium text-slate-700">
              <div
                class="relative grid h-16 w-16 items-center justify-center rounded-xl border border-transparent bg-transparent text-white hover:bg-slate-50 has-[:checked]:border-purple-500 has-[:checked]:bg-purple-50 has-[:checked]:text-purple-50 forced-colors:border-0"
              >
                <input
                  id="theme-4"
                  type="radio"
                  name="themes"
                  class="appearance-none forced-colors:appearance-auto"
                />
                <p class="hidden forced-colors:block">Purple</p>
                <div
                  class="absolute left-3 top-3 h-6 w-6 rounded-full bg-purple-200 forced-colors:hidden"
                ></div>
                <div
                  class="absolute bottom-3 right-3 h-6 w-6 rounded-full bg-purple-500 ring-2 ring-current forced-colors:hidden"
                ></div>
              </div>
            </label>
          </div>
        </form>
      </div>

      <div
        class="max-w-md overflow-hidden rounded-lg bg-white shadow-xl ring-1 ring-slate-900/5 sm:max-w-2xl"
      >
        <div class="flex flex-col sm:flex-row">
          <div class="sm:shrink-0">
            <img
              class="h-[200px] w-full object-cover object-bottom sm:w-[193px] sm:object-center"
              src="https://images.unsplash.com/photo-1637734433731-621aca1c8cb6?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=404&amp;q=80"
              width="202"
              height="192"
              alt="Beautiful abstract building in the sun"
            />
          </div>
          <div class="space-y-2 p-6 2xl:p-8">
            <div class="text-sm font-medium leading-6 text-indigo-600">
              Company retreats
            </div>
            <a
              href="#"
              class="block text-base font-semibold leading-6 text-slate-900 hover:underline"
              >Incredible accommodation for your team</a
            >
            <p class="text-sm leading-6 text-slate-600">
              Looking to take your team away on a retreat to enjoy awesome food
              and take in some sunshine? We have a list of places to do just
              that.<!-- -->
            </p>
          </div>
        </div>
      </div>

      <div class="w-72 bg-white px-8 py-6 shadow sm:w-96 sm:px-12 sm:py-8">
        <div class="flex items-center space-x-2 text-base">
          <h4 class="text-base font-semibold text-slate-900">Contributors</h4>
          <span
            class="rounded-full bg-slate-100 px-2 py-1 text-xs font-semibold text-slate-700"
            >204</span
          >
        </div>
        <div class="mt-3 flex -space-x-2 overflow-hidden">
          <img
            class="inline-block h-12 w-12 rounded-full ring-2 ring-white"
            src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
            alt=""
          />
          <img
            class="inline-block h-12 w-12 rounded-full ring-2 ring-white"
            src="https://images.unsplash.com/photo-1550525811-e5869dd03032?ixlib=rb-1.2.1&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
            alt=""
          />
          <img
            class="inline-block h-12 w-12 rounded-full ring-2 ring-white"
            src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2.25&amp;w=256&amp;h=256&amp;q=80"
            alt=""
          />
          <img
            class="inline-block h-12 w-12 rounded-full ring-2 ring-white"
            src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
            alt=""
          />
          <img
            class="inline-block h-12 w-12 rounded-full ring-2 ring-white"
            src="https://images.unsplash.com/photo-1517365830460-955ce3ccd263?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=256&amp;h=256&amp;q=80"
            alt=""
          />
        </div>
        <div class="mt-3 text-sm font-medium">
          <a href="#" class="text-blue-500">+ 198 others</a>
        </div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2">
        <div class="p-8 pt-7">
          <p class="mb-2 text-sm font-medium text-slate-500">Light mode</p>
          <div
            class="rounded-lg bg-white px-6 py-8 shadow-xl ring-1 ring-slate-900/5"
          >
            <div>
              <span
                class="inline-flex items-center justify-center rounded-md bg-indigo-500 p-2 shadow-lg"
              >
                <svg
                  class="h-6 w-6 text-white"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"
                  ></path>
                </svg>
              </span>
            </div>
            <h3
              class="mt-5 text-base font-medium tracking-tight text-slate-900"
            >
              Writes Upside-Down
            </h3>
            <p class="mt-2 text-sm text-slate-500">
              The Zero Gravity Pen can be used to write in any orientation,
              including upside-down. It even works in outer space.
            </p>
          </div>
        </div>
        <div class="bg-slate-900 p-8 pt-7">
          <p class="mb-2 text-sm font-medium text-slate-400">Dark mode</p>
          <div
            class="rounded-lg bg-slate-800 px-6 py-8 shadow-xl ring-1 ring-slate-900/5"
          >
            <div>
              <span
                class="inline-flex items-center justify-center rounded-md bg-indigo-500 p-2 shadow-lg"
              >
                <svg
                  class="h-6 w-6 text-white"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"
                  ></path>
                </svg>
              </span>
            </div>
            <h3 class="mt-5 text-base font-medium tracking-tight text-white">
              Writes Upside-Down
            </h3>
            <p class="mt-2 text-sm text-slate-400">
              The Zero Gravity Pen can be used to write in any orientation,
              including upside-down. It even works in outer space.
            </p>
          </div>
        </div>
      </div>

      <div class="w-72 bg-white px-8 py-6 shadow sm:w-96 sm:px-12 sm:py-8">
        <div>
          <img
            class="rounded"
            src="https://images.unsplash.com/photo-1452784444945-3f422708fe5e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=512&amp;q=80"
            width="512"
            height="341"
            alt="Beach"
          />
          <div class="mt-2">
            <div>
              <div
                class="text-xs font-bold uppercase tracking-wider text-slate-600"
              >
                Private Villa
              </div>
              <div class="font-bold leading-snug text-slate-700">
                <a href="#" class="hover:underline"
                  >Relaxing All-Inclusive Resort in Cancun</a
                >
              </div>
              <div class="mt-2 text-sm text-slate-600">$299 USD per night</div>
            </div>
          </div>
        </div>
      </div>

      <div class="max-w-lg bg-white px-6 py-8 shadow">
        <blockquote
          class="text-center text-2xl font-semibold italic text-slate-900"
        >
          When you look
          <span
            class="relative inline-block before:absolute before:-inset-1 before:block before:-skew-y-3 before:bg-pink-500"
            ><span class="relative text-white">annoyed</span></span
          >
          all the time, people think that you're busy.
        </blockquote>
      </div>

      <a
        href="#"
        class="group block max-w-xs space-y-3 rounded-lg bg-white p-4 shadow-lg ring-1 ring-slate-900/5 hover:bg-sky-500 hover:ring-sky-500"
      >
        <div class="flex items-center space-x-3">
          <svg
            class="h-6 w-6 stroke-sky-500 group-hover:stroke-white"
            fill="none"
            viewBox="0 0 24 24"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M11 19H6.931A1.922 1.922 0 015 17.087V8h12.069C18.135 8 19 8.857 19 9.913V11"
            ></path>
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M14 7.64L13.042 6c-.36-.616-1.053-1-1.806-1H7.057C5.921 5 5 5.86 5 6.92V11M17 15v4M19 17h-4"
            ></path>
          </svg>
          <h3
            class="text-sm font-semibold text-slate-900 group-hover:text-white"
          >
            New project
          </h3>
        </div>
        <p class="text-sm text-slate-500 group-hover:text-white">
          Create a new project from a variety of starting templates.
        </p>
      </a>

      <div class="bg-white px-6 py-4 shadow">
        <nav class="flex justify-center space-x-4">
          <a
            href="#/dashboard"
            class="rounded-lg px-3 py-2 font-bold text-slate-700 hover:bg-slate-100 hover:text-slate-900"
            >Home</a
          ><a
            href="#/team"
            class="rounded-lg px-3 py-2 font-bold text-slate-700 hover:bg-slate-100 hover:text-slate-900"
            >Team</a
          ><a
            href="#/projects"
            class="rounded-lg px-3 py-2 font-bold text-slate-700 hover:bg-slate-100 hover:text-slate-900"
            >Projects</a
          ><a
            href="#/reports"
            class="rounded-lg px-3 py-2 font-bold text-slate-700 hover:bg-slate-100 hover:text-slate-900"
            >Reports</a
          >
        </nav>
      </div>

      <div class="max-w-sm bg-white px-6 pb-5 pt-6 shadow">
        <form>
          <div>
            <label
              for="email-2"
              class="block text-sm font-medium text-slate-700"
              >Email</label
            >
            <div class="mt-1">
              <input
                id="email-2"
                type="email"
                name="email"
                class="peer block w-full rounded-md border border-slate-300 bg-white px-3 py-2 placeholder-slate-400 shadow-sm invalid:border-pink-500 invalid:text-pink-600 focus:border-sky-500 focus:outline-none focus:ring-1 focus:ring-sky-500 focus:invalid:border-pink-500 focus:invalid:ring-pink-500 disabled:border-slate-200 disabled:bg-slate-50 disabled:text-slate-500 disabled:shadow-none sm:text-sm"
                value="george@krugerindustrial."
                placeholder="you@example.com"
              />
              <p
                class="invisible mt-2 text-sm text-pink-600 peer-invalid:visible"
              >
                Please provide a valid email address.
              </p>
            </div>
          </div>
        </form>
      </div>
    </div>
  </NuxtLayout>
</template>
