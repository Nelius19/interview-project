<template>
    <div>
        <div class="max-w-md mx-auto bg-white p-8 shadow-md">
        <h2 class="text-2xl font-bold mb-4">Create an account</h2>
        <form>
            <div class="mb-4">
                <label for="firstname" class="block font-semibold text-left mb-1">Firstname:</label>
                <input type="text" name="firstname" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Enter your firstname" />
            </div>
            <div class="mb-4">
                <label for="lastname" class="block font-semibold text-left mb-1">Lastname:</label>
                <input type="text" name="lastname" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Enter your lastname" />
            </div>
            <div class="mb-4">
                <label for="password" class="block font-semibold text-left mb-1">Password:</label>
                <input type="password" name="password" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Enter your password" />
            </div>
            <div class="mb-4">
                <label for="confirm-password" class="block font-semibold text-left mb-1">Confirm password:</label>
                <input type="password" name="password" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Re-enter password" />
            </div>
            <div class="mb-4">
                <label for="email" class="block font-semibold text-left mb-1">Email:</label>
                <input type="email" name="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Enter your email address" />
            </div>
            <small class="text-left">Already have an account? Sign In</small>
            <button type="submit" class="font-bold mt-4 bg-blue-900 text-white px-4 py-1 w-full rounded-md hover:bg-blue-600 uppercase">create account</button>
        </form>
    </div>
    </div>
</template>

