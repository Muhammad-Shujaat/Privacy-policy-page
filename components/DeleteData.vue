<template>
    <div class="p-10">
        <form class="w-full max-w-[60rem] flex flex-col  gap-y-5 ">
            <div class="text-[1.2rem] w-full md:w-[70%] lg:w-1/2 sm:text-[1.5rem]  font-bold  py-5">
                <h2 class="">Data Deletion Request</h2>
            </div>

            <input
                class="border-[#c1c1c1] border-[1px] h-[3rem] w-full md:w-[70%] lg:w-1/2 max-w-full px-[1.25rem] font-[300] text-[0.85] outline-[#c1c1c146]"
                type="text" placeholder="Your Name*" required>


            <input
                class="border-[#c1c1c1] border-[1px] h-[3rem] w-full md:w-[70%] lg:w-1/2 max-w-full px-[1.25rem] font-[300] text-[0.85] outline-[#c1c1c146]"
                type="text" placeholder="Company Name" required>


            <input
                class="border-[#c1c1c1] border-[1px] h-[3rem] w-full md:w-[70%] lg:w-1/2 max-w-full px-[1.25rem] font-[300] text-[0.85] outline-[#c1c1c1]"
                type="email" placeholder="Email Address*" required>


            <input
                class="border-[#c1c1c1] border-[1px] h-[3rem] w-full md:w-[70%] lg:w-1/2 max-w-full px-[1.25rem] font-[300] text-[0.85] outline-[#c1c1c1]"
                name="Number" type="tel" placeholder="Phone Number*" required>

            <div class="flex gap-5">
                <label class="text-lg font-semibold">Delete User Account:</label>
                <label for="yes" class="flex gap-2 items-center">

                    <input type="radio" v-bind:id="'yes'" name="user" value="aldksfj" required>
                    Yes
                </label>
                <label for="No" class="flex gap-2 items-center">
                    <input type="radio" v-bind:id="'No'" name="user" required>
                    No
                </label>
            </div>
            <div class="flex gap-5">
                <label class="text-lg font-semibold">Delete Data Only:</label>
                <label for="y" class="flex gap-2 items-center">

                    <input type="radio" v-bind:id="'y'" name="data" value="aldksfj" required>
                    Yes
                </label>
                <label for="N" class="flex gap-2 items-center">
                    <input type="radio" v-bind:id="'N'" name="data" required>
                    No
                </label>
            </div>

            <textarea
                class="block p-2.5 w-full md:w-[70%] lg:w-1/2 max-w-full text-sm text-gray-900 border-[#c1c1c1] border-[1px] outline-[#c1c1c1] h-[11rem]"
                name="message" placeholder="Message*"></textarea>


            <div class="w-full md:w-[8%] lg:w-1/2 flex  items-center my-6"><input
                    class="border-[#c1c1c1] border-[1px] w-max px-8 bg-[#11117E] hover:bg-[#18012c] text-lg text-white h-14 leading-7 font-[400]"
                    type="submit" value="SEND DELETE REQUEST"></div>


        </form>
    </div>
</template>