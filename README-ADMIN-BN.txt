আমার প্রবাস জীবনের গল্প — Admin Panel

গুরুত্বপূর্ণ: শুধু এই ফাইলগুলো GitHub-এ আপলোড করলেই Admin Panel লগইন চালু হবে না।
প্রথমে GitHub repository-টি Netlify site-এর সঙ্গে connect করতে হবে এবং Netlify-তে GitHub OAuth authentication provider সেট করতে হবে।
তারপর Netlify site dashboard > Project configuration > Access & security > OAuth > Authentication providers (GitHub) থেকে GitHub OAuth App-এর Client ID ও Client Secret যোগ করতে হবে।
GitHub OAuth App-এর Authorization callback URL হবে:
https://api.netlify.com/auth/done

Repository: amarprobasjibonergolpo/amarprobasjibonergolpo
Branch: main
Admin URL: https://amar-probas-jiboner-golpo.netlify.app/admin/

নিরাপত্তা: GitHub OAuth App-এর Client Secret কখনো এই ফোল্ডারের কোনো ফাইলে লিখবেন না বা কাউকে পাঠাবেন না।
