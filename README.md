# ستۆکفڵۆ | Stockflow

تۆماری بازرگانی بە زمانی کوردیی سۆرانی بۆ بەڕێوەبردنی کڕین، فرۆشتن، کاڵا، باڵانسی کڕیار و فرۆشیار، و گەیاندن.

## بەکارهێنان

ئەپەکە وێبگەڕی نوێ پێویست ناکات: `index.html` بکەرەوە. خاوەن بە PINی `1122` و گەیەنەر بە PINی `3344` دەچنە ژوورەوە.

## بڵاوکردنەوە لە Cloudflare

ئەم پرۆژەیە وێبسایتێکی static ـە و ڕێکخستنی Workers Static Assets ـی Wrangler لە `wrangler.jsonc` هەیە.

- لە Cloudflare Dashboard، Workers & Pages بکەرەوە و Create application > Import a repository هەڵبژێرە.
- کۆگای GitHub ـی `sakarsellingproducts` بەستەوە و branch ـی `main` دیاری بکە.
- چونکە build step نییە، هیچ build command یان output folder دانەنێ.
- یان بە Wrangler CLI، دوای چوونەژوورەوە بە هەژماری Cloudflare، `npx wrangler deploy` جێبەجێ بکە.

## گرنگ

داتاکان لە localStorage ـی ئەو وێبگەڕەدا پاشەکەوت دەبن و PIN تەنها ڕۆڵی ناو ڕووکار دەگۆڕێت. ئەم وەشانە هێشتا داتای هاوبەش لە نێوان ئامێرەکان یان پاراستنی backendی نییە. بۆ بەکارهێنانی چەند ئامێر، پێویستە backend و بنکەدراوەی هاوبەش زیاد بکرێت.

فۆنتی Serchia Baran لە `fonts/SerchiaBaran.ttf` دانراوە و لە ڕووکاردا بەکاردێت.
