1) What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
ans: getElementById শুধুমাত্র একটি element সিলেক্ট করবে
     querySelector / querySelectorAll CSS selector ব্যবহার করে element(s) সিলেক্ট করে।
     getElementsByClassName একাধিক element সিলেক্ট করতে পারে

2) How do you **create and insert a new element into the DOM**?
   ans: নতুন element বানাতে document.createElement() ব্যবহার করে, তারপর parent element-এ ঢোকাতে appendChild() ব্যবহার করে।
3)What is **Event Bubbling** and how does it work?
ans: Event Bubbling হলো একটি JavaScript ইভেন্টের প্রক্রিয়া যেখানে কোনো child element এ event (যেমন click) ঘটলে, সেই ইভেন্ট পরপর parent element-গুলোর দিকে চলে যায়।
4) What is **Event Delegation** in JavaScript? Why is it useful?
   ans: Event Delegation হলো এমন একটি পদ্ধতি যেখানে child element-এর পরিবর্তে তার parent element-এ event listener বসায়, তারপর সেই listener event bubbling ব্যবহার করে কোন child element-click হয়েছে তা চেক করে handle করে।
5) What is the difference between **preventDefault() and stopPropagation()** methods?
   ans: preventDefault() → element-এর default browser behavior বন্ধ করে। stopPropagation() → ইভেন্টকে উপরের parent element-এ যাওয়া বন্ধ করে দেয়।

     
     
