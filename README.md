# Inspiration

SafeSignal came from a reality women live with every day: feeling unsafe just for being outside alone, walking home, riding with a stranger, or crossing a parking garage at night. Too often, women have to plan their lives around “what if,” and that’s not okay. We built SafeSignal to give women a fast, believable way to feel protected in the moment, so confidence, freedom, and independence don’t have to come with fear.

---

# What it does

SafeSignal is a personal safety app built to provide fast, discreet help during emergencies. With a simple shake of the phone, users can instantly trigger alerts and one's location with their preferred emergency contacts. The app also includes an AI companion that simulates a realistic phone conversation, acting as a voice deterrent in threatening situations while keeping the user engaged and supported. 

To further enhance safety, SafeSignal features an interactive map that displays nearby emergency blue light stations with real-time distance information and quick navigation, enabling users to quickly connect with campus security.

---

# How we built it

We built SafeSignal as a cross-platform mobile app using React Native (TypeScript/JavaScript), so it runs smoothly on both iOS and Android with one shared codebase. 

For emergency activation, we use Expo’s accelerometer to detect a shake gesture and trigger safety actions instantly. We capture live location using the Google Maps API, which lets us show accurate real-time positioning, calculate distances, and guide users toward nearby emergency blue-light stations with clear navigation. 

To strengthen deterrence in tense moments, we integrated ElevenLabs AI voice to simulate realistic phone call conversations, helping users appear connected and supported when they need it most. 

By combining mobile development, gesture-based triggering, Google Maps location services, and AI voice technology, SafeSignal delivers fast, discreet, and practical safety support.

---

# Challenges we ran into

One of our major challenges was resolving merge conflicts as multiple contributors worked on the same files with different implementations, making integration complex and time-consuming. 

We also faced significant obstacles within the settings module, particularly in building a dependable system to trigger alerts and reliably send messages to emergency contacts under all conditions. 

Development was further complicated by difficulties with Expo Go, where generating QR codes and ensuring that new code changes consistently propagated to the live application often slowed our testing and debugging process. 

In addition, the standard version of ElevenLabs imposed notable limitations, including restricted voice options and audio that sounded artificial. To overcome this, we put extra effort into sourcing and integrating external sound effects to create a more convincing and realistic user experience.

---

# Accomplishments that we're proud of

In just 24 hours, we took SafeSignal from an idea to a working product with live location tracking that can be shared instantly when it matters most. 

We also built a hands-free emergency trigger using phone motion sensing, so even if someone cannot safely unlock their phone or tap a button, a quick shake can start the safety flow and alert emergency contacts. 

The biggest accomplishment was getting all the features to work together. We ran into constant issues with permissions, location reliability, sensors, and app flow stability, but we kept pushing until the experience felt smooth and dependable.

---

# What we learned

We learned how to take a bunch of separate features and make them feel like one smooth, reliable app. It pushed us to think more like real product builders, not just coders, with cleaner architecture, better testing habits, and clearer teamwork. 

Most of all, we learned that clear communication and steady iteration matter more than trying to make everything perfect on the first try.

---

# What's next for SafeSignal

Looking ahead, we see major opportunities to expand SafeSignal’s capabilities. 

Currently, the shake trigger functions only when the application is open, but a key future goal is enabling background activation so alerts can be initiated even when the phone is locked. 

We also aim to introduce customizable trigger sensitivity and gesture configurations to minimize accidental activations during everyday movement. 

Beyond detection, we plan to build a dedicated chat interface that allows users to quickly communicate the details of their situation and provide richer contextual information. 

Finally, we envision significantly advancing our AI companion to deliver more natural, human-like phone conversations, creating stronger deterrence and a greater sense of real-time support during emergencies.
