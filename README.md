<p align="center">
  <h1 align="center">FocusGuard – Website Blocker Python</h1>
  <p align="center">
    A simple Python automation project that blocks distracting websites during working or study hours by modifying the system hosts file.
  </p>
</p>

---

## 👥 Team Members

This project was developed collaboratively by students of Rajkiya Engineering College, Ambedkar Nagar.

<table align="center">
  <tr>
    <td align="center" width="150">
      <b>Abhishek Kumar Kalaujiya</b><br />
      2407370130002
    </td>

    <td align="center" width="150">
      <b>Abhishek Rao</b><br />
      2407370130004
    </td>

    <td align="center" width="150">
      <b>Anikesh Kumar</b><br />
      2407370130016
    </td>

    <td align="center" width="150">
      <b>Prince Kannaujiya</b><br />
      2407370130046
    </td>
  </tr>

  <tr>
    <td align="center" width="150">
      <b>Saransh Sonkar</b><br />
      2407370130056
    </td>

    <td align="center" width="150">
      <b>Vishnu Pratap Singh</b><br />
      2407370130069
    </td>

    <td align="center" width="150">
      <b>Yogendra</b><br />
      2407370130070
    </td>
  </tr>
</table>

<p align="center">
  <em>B.Tech IT — Rajkiya Engineering College, Ambedkar Nagar</em>
</p>

---

## 📌 Overview

FocusGuard is a Python-based website blocker designed to improve productivity by restricting access to distracting websites during working or study hours.

The project works by modifying the system hosts file and redirecting selected websites to the localhost address (`127.0.0.1`).

---

## ⚙️ Technologies Used

- Python
- File Handling
- Datetime Module
- OS Module

---

## 🧠 How it Works

The script redirects blocked websites to:

```txt
127.0.0.1
```

Example:

```txt
127.0.0.1 facebook.com
```

This prevents the browser from accessing the real website.

The websites are automatically unblocked after working hours.

---

## 🌐 Websites to Block

Open `app.py` and edit:

```python
sites_to_block = [
    "facebook.com",
    "youtube.com",
    "instagram.com"
]
```

---

## ⏰ Setting Working Hours

Edit the last line in `app.py`:

```python
block_websites(9, 21)
```

This blocks websites from 9 AM to 9 PM.

---

## 💻 Hosts File Locations

### Windows

```txt
C:\Windows\System32\drivers\etc\hosts
```

### Linux

```txt
/etc/hosts
```

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/dark-shadowblade/BlockSite.git
cd BlockSite
```

Run the script:

```bash
python app.py
```

---

## 📂 Project Structure

```text
BlockSite/
│
├── app.py
├── app v2.py
├── README.md
└── screenshots/
```

---

## 📌 Note

Run the script as Administrator because modifying the hosts file requires system permission.

---

## 📖 Conclusion

FocusGuard demonstrates practical use of Python automation and file handling by controlling website access through hosts file modification.
