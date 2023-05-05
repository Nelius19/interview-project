<template>
    <div class="max-w-md mx-auto bg-white p-8 shadow-md">
        <h2 class="text-2xl font-bold uppercase mb-8">Login</h2>
        <form>
            <div class="mb-4">
            <label for="email_address" class="block font-semibold text-left uppercase mb-1">Email Address:</label>
            <input type="email" name="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" autocomplete="none" placeholder="Enter email address" />
            </div>
            <div class="mb-4">
            <label for="password" class="block font-semibold text-left uppercase mb-1">password:</label>
            <input type="password" name="password" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Enter password" />
            </div>
            <small class="text-left">Don't have an account? Sign Up</small>
            <button type="submit" class="font-bold mt-4 mb-3 bg-blue-900 text-white px-4 py-1 w-full rounded-md hover:bg-blue-600 button-sm">LOGIN</button>
            <small class="text-right font-bold">Forget password?</small>
        </form>
    </div>
</template>


