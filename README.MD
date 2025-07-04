# eShift Shift Collector (Archived)

🛠️ **Open-source robot for eShift shift booking (Tesco)**  
📬 Automatically clicks shift links as soon as they arrive via email  
⚠️ **This project is archived** – but might still be useful in some countries

## ⚡ What is this?

This tool was built for Tesco part-time workers using the eShift system.  
In short: when eShift sends new shifts via email, this bot immediately clicks the links to sign you up – faster than a human ever could.  
👉 Perfect if you wanted good shifts without refreshing your inbox every second.

## ❌ Why is it archived?

Tesco in my country moved to a new system, so eShift is no longer used here.  
However, I’ve heard it’s still active in some regions – so feel free to dig into it **for educational purposes only**.

## ⚠️ Disclaimer

> **FOR EDUCATIONAL PURPOSES ONLY.**  
> No support. No docs. No guarantees.  
> If you know Python and enjoy reverse engineering, go for it. If not – good luck, nerd.

## 🧠 How it (probably) works

1. Listens to your inbox using IMAP (e.g. Gmail)
2. When a new eShift email arrives, it extracts the shift booking links
3. Automatically opens those links using `app.py` to claim the shifts
4. Login credentials are stored in `appointments.db`

## 🔧 What you need

- Python 3.x
- `.env` file with IMAP settings (e.g. your email server)
- A filled-out `appointments.db` with your eShift login (see example)


## 📁 Files & Structure

- `appointments.db` – contains your eShift credentials (example included)
- `.env` – fill in `IMAP_SERVER`, `EMAIL`, `EMAIL_PASSWORD`, etc.

## 🤷‍♂️ Documentation?

None. I was too lazy.  
But hey – it worked for me. If you get it working, congrats.

---

🧙‍♂️ Nerds only past this point. May the source be with you.
