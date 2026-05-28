Multi Plus TV Premium Mobile - Rapid Switch No Black Fix v34 Flat ZIP

এই update-এ black screen/grey play image সমস্যার জন্য strong method ব্যবহার করা হয়েছে:
1) Rapid channel change debounce system যোগ করা হয়েছে, তাই দ্রুত চাপলেও শুধু final channel load হবে
2) Android/WebView native black frame leak hide করার জন্য deep-blue video cover যোগ করা হয়েছে
3) source destroy/load হওয়ার আগে cover force করে দেওয়া হয়
4) real video frame ready না হওয়া পর্যন্ত cover থাকবে
5) fast channel হলে cover দ্রুত চলে যাবে
6) default grey play placeholder আর দেখা যাবে না
7) Home page brightness auto increase fix রাখা হয়েছে
8) mute auto-unmute এবং pause auto-play fix রাখা হয়েছে
9) বাকি সব mobile v33/v32/v31 function unchanged রাখা হয়েছে


v35 only update: loading text/cover replaced with premium 3D loader model.
