<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>英语单词闪卡</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
<script src="https://cdn.tailwindcss.com"></script>
<script>
tailwind.config = {
theme: {
extend: {
colors: {
primary: '#4F46E5',
secondary: '#6366F1'
},
borderRadius: {
'none': '0px',
'sm': '2px',
DEFAULT: '4px',
'md': '8px',
'lg': '12px',
'xl': '16px',
'2xl': '20px',
'3xl': '24px',
'full': '9999px',
'button': '4px'
}
}
}
}
</script>
<style>
body {
font-family: 'Inter', sans-serif;
min-height: 1024px;
background-color: #F3F4F6;
}
.card {
transition: transform 0.2s ease-in-out;
}
.card:hover {
transform: translateY(-4px);
}
.phonetic {
color: #6B7280;
font-size: 14px;
}
.example {
color: #4B5563;
font-size: 14px;
line-height: 1.5;
}
.play-button {
cursor: pointer;
color: #4F46E5;
}
.play-button:hover {
color: #4338CA;
}
</style>
</head>
<body>
<div class="container mx-auto px-4 py-12">
<div class="flex justify-between items-center mb-12">
<h1 class="text-3xl font-bold text-gray-800">英语单词闪卡</h1>
<button class="flex items-center gap-2 px-4 py-2 bg-primary text-white rounded-button hover:bg-opacity-90">
<i class="fas fa-share-alt"></i>
<span class="whitespace-nowrap">分享页面</span>
</button>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
<!-- Afternoon -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/32012beb622a026c263bf418f369e134.jpg"
alt="Afternoon"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Afternoon</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/ˌɑːf.təˈnuːn/</p>
<div class="example flex items-center justify-center gap-2">
<p>We usually have tea in the afternoon.</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
<!-- Alex -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/f669f8b6618288f9d56c227cfe357eb5.jpg"
alt="Alex"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Alex</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/ˈælɪks/</p>
<div class="example flex items-center justify-center gap-2">
<p>Alex is my best friend.</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
<!-- Alice -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/4505c1b66acb1b0a2483ff0dcfa5bd1d.jpg"
alt="Alice"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Alice</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/ˈælɪs/</p>
<div class="example flex items-center justify-center gap-2">
<p>Alice works in a hospital.</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
<!-- Alien -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/75834eec9d02c756669ea3a28fae0fb0.jpg"
alt="Alien"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Alien</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/ˈeɪ.li.ən/</p>
<div class="example flex items-center justify-center gap-2">
<p>Do you believe in aliens?</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
<!-- Angry -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/fa517aaae04e508a9bd90a0e5baf062b.jpg"
alt="Angry"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Angry</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/ˈæŋ.ɡri/</p>
<div class="example flex items-center justify-center gap-2">
<p>He is angry about the test score.</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
<!-- Animal -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/c41dfa0e21eb15a4cdbfbe6a9643d4bc.jpg"
alt="Animal"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Animal</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/ˈæn.ɪ.məl/</p>
<div class="example flex items-center justify-center gap-2">
<p>Dogs are my favorite animals.</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
<!-- Apartment -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/b01ec53d755a2a3024945a911a611008.jpg"
alt="Apartment"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Apartment</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/əˈpɑːt.mənt/</p>
<div class="example flex items-center justify-center gap-2">
<p>She lives in a small apartment.</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
<!-- Apple -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/86428a2c4ecf38e9e16888a4e4797fc9.jpg"
alt="Apple"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Apple</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/ˈæp.əl/</p>
<div class="example flex items-center justify-center gap-2">
<p>I eat an apple every day.</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
<!-- Arm -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/0b7e73850d2a968f83d81ecb540f0c7c.jpg"
alt="Arm"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Arm</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/ɑːm/</p>
<div class="example flex items-center justify-center gap-2">
<p>He hurt his arm while playing football.</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
<!-- Armchair -->
<div class="card bg-white rounded-lg shadow-md p-4">
<div class="aspect-square mb-4 overflow-hidden rounded-lg">
<img src="https://ai-public.mastergo.com/ai/img_res/8df3b5765eb2b491841ba668f736a9eb.jpg"
alt="Armchair"
class="w-full h-full object-cover">
</div>
<div class="text-center">
<div class="flex items-center justify-center gap-2 mb-2">
<h2 class="text-xl font-semibold">Armchair</h2>
<i class="fas fa-play-circle play-button text-lg"></i>
</div>
<p class="phonetic mb-2">/ˈɑːm.tʃeər/</p>
<div class="example flex items-center justify-center gap-2">
<p>I like to sit in the armchair.</p>
<i class="fas fa-volume-up play-button"></i>
</div>
</div>
</div>
</div>
</div>
<script>
const playButtons = document.querySelectorAll('.play-button');
playButtons.forEach(button => {
button.addEventListener('click', () => {
const word = button.closest('.card').querySelector('h2').textContent;
const isExample = button.parentElement.classList.contains('example');
const text = isExample ? button.previousElementSibling.textContent : word;
const audio = new Audio(`https://dict.youdao.com/dictvoice?type=0&audio=${encodeURIComponent(text)}`);
audio.play();
});
});
document.querySelector('button').addEventListener('click', async () => {
try {
await navigator.share({
title: '英语单词闪卡',
text: '来学习英语单词吧！',
url: window.location.href
});
} catch (err) {
alert('您的浏览器不支持分享功能');
}
});
</script>
</body>
</html>
