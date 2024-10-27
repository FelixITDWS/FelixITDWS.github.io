<template>
    <div class = "bg-sky-100 py-2">
        <p class = "px-6 py-4 text-2xl text-gray-700">預設佈局</p>
        <slot name = "header"/>
        <slot/>
        <slot name = "footer"/>
    </div>
</template>