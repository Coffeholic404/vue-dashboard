<template>
    <div class=" fixed left-0 top-0 w-64 h-full bg-gray-900 p-4">
        <a href="#" class="flex items-center pb-4 border-b border-b-gray-800">
            <img src="https://placehold.co/32x32" alt="" class="w-8 h-8 rounded object-cover">
            <span class=" text-lg font-bold text-white ml-3">Logo</span>
        </a>
        <ul class=" mt-4">
            <li class=" mb-1 group active">
                <a href="#" class=" flex items-center py-2 px-4 gap-2 text-gray-300 hover:bg-gray-950 hover:text-gray-100 rounded-md group-[.active]:bg-gray-800 group-[.active]:text-white">
                    <RiHome2Line class=" text-lg"/>
                    <span class=" text-sm">DashBoard</span>
                </a>
            </li>
            <li class=" mb-1 group">
                <a href="#" class=" flex items-center py-2 px-4 gap-2 text-gray-300 hover:bg-gray-950 hover:text-gray-100 rounded-md group-[.active]:bg-gray-800 group-[.active]:text-white">
                    <RiInstanceLine class=" text-lg"/>
                    <span class=" text-sm">Orders</span>
                    <RiArrowRightSLine class=" ml-auto group-[.active]:rotate-90"/>
                </a>
                <ul class=" pl-7 mt-2">
                    <li class="mb-4">
                        <a href="#" class=" text-gray-300 text-sm flex items-center hover:text-gray-100 before:contents-[''] before:w-1 before:h-1 before:rounded-full before:bg-gray-300 before:mr-3"> Active Order</a></li>
                    <li class="mb-4">
                        <a href="#" class=" text-gray-300 text-sm flex items-center hover:text-gray-100 before:contents-[''] before:w-1 before:h-1 before:rounded-full before:bg-gray-300 before:mr-3"> Completed Order</a></li>
                    <li class="mb-4">
                        <a href="#" class=" text-gray-300 text-sm flex items-center hover:text-gray-100 before:contents-[''] before:w-1 before:h-1 before:rounded-full before:bg-gray-300 before:mr-3"> Canceled Order</a></li>
                </ul>
            </li>
            <li class=" mb-1 group">
                <a href="#" class=" flex items-center py-2 px-4 gap-2 text-gray-300 hover:bg-gray-950 hover:text-gray-100 rounded-md group-[.active]:bg-gray-800 group-[.active]:text-white">
                    <RiFlashlightLine class=" text-lg"/>
                    <span class=" text-sm">Services</span>
                    <RiArrowRightSLine class=" ml-auto group-[.active]:rotate-90"/>
                </a>
                <ul class=" pl-7 mt-2">
                    <li class="mb-4">
                        <a href="#" class=" text-gray-300 text-sm flex items-center hover:text-gray-100 before:contents-[''] before:w-1 before:h-1 before:rounded-full before:bg-gray-300 before:mr-3"> Mange Services</a></li>
                </ul>
            </li>
            <li class=" mb-1 group">
                <a href="#" class=" flex items-center py-2 px-4 gap-2 text-gray-300 hover:bg-gray-950 hover:text-gray-100 rounded-md group-[.active]:bg-gray-800 group-[.active]:text-white">
                    <RiSettings2Line class=" text-lg"/>
                    <span class=" text-sm">Settings</span>
                </a>
            </li>
        </ul>
    </div>
</template>

<script setup>
import { RiHome2Line, RiInstanceLine, RiFlashlightLine, RiSettings2Line, RiArrowRightSLine } from "@remixicon/vue";

const sideBarDropDown = () => {
    
}
</script>

