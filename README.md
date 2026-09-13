# 🏦 LoanBridge360 — Free Loan Tracker & Interest Calculator

**LoanBridge360** is a free, secure web app to track personal loans between friends & family.
Calculate interest (simple or compound), verify payments, share entries with partners, and manage debt — all in one place.

🔗 **Live App**: [loanbridge360.vercel.app](https://loanbridge360.vercel.app/)
📖 **Documentation**: [loanbridge360.vercel.app/documentation](https://loanbridge360.vercel.app/documentation)

---

## ✨ What is LoanBridge360?

LoanBridge360 is a simple, secure way to keep track of money you've lent or borrowed between friends and family — with **automatic interest calculation**, so you never have to do the math by hand.

With LoanBridge360 you can:
- 📋 Record loans you've given or received, with **simple or compound interest**
- 📈 See exactly how much is owed today, **updated automatically every day**
- 🤝 Share a loan entry with the other person so **you both see the same numbers**
- 💸 Log payments and get them **verified by the other side**
- 🌙 Switch between **light and dark themes**, and view amounts in your preferred currency

---

## 🚀 Getting Started

Creating an account takes less than a minute.

1. Open [LoanBridge360](https://loanbridge360.vercel.app/) and choose **Sign Up**, or continue with **Sign in with Google** for one-tap access.
2. If signing up with email, use a **real email address** — temporary or disposable email addresses aren't accepted, to keep the community trustworthy.
3. Set a password (at least 6 characters) and confirm it.
4. Check your email inbox and click the **confirmation link**.
5. You're in! You'll land on your dashboard, ready to add your first loan.

> **Forgot your password?** Use **Forgot password?** on the sign-in screen to get a reset link by email.

---

## 🔧 All Features Explained

### 💰 1. Loan Tracking
- Add a loan in either direction:
  - **💵 I Received Money** — you borrowed, you owe someone.
  - **💳 I Gave Money** — you lent, someone owes you.
- Works for **Banks** or **Individuals / People**.
- Choose **Simple** or **Compound** interest.
- Interest rate can be **Yearly** or **Monthly**.
- The app **automatically calculates**: interest earned so far, total amount payable, amount already paid, and remaining balance — always up to date, no manual math needed.
- See an **upcoming schedule** — what you'll owe (or be owed) over the next 6 periods.
- Edit or delete any entry anytime.
- Once a loan is fully settled, **Mark it as Closed** — it moves to your Archive. You can **Reopen** it later if needed.

### 🤝 2. Shared Loans — Track Together With the Other Person
Instead of both people keeping separate notes (which never match!), you can connect a loan so both sides see the **same numbers**:
- Open a loan → click **Connect** → send an invite to the other person by **email**.
- Once they accept, the loan becomes a shared entry — both of you see the same balance and history.
- Either side can log a payment; the other side confirms it, so both records always agree.
- You can control whether they're allowed to add entries, **remove** them anytime, or they can choose to **leave** the shared loan themselves.

### ✅ 3. Payment Verification (No Fake Entries)
- Open the loan and choose **Add Payment**, then enter the amount and date.
- On a shared loan, the payment shows as **⏳ Pending** until the other person verifies it from their **Settings → Pending Verifications** panel.
- They must **Verify ✅** it for it to count, or **Reject ❌** it with a note explaining why.
- Once verified, the payment is applied to **interest first, then principal** — the same way most real-world loans work.
- This means neither side can secretly change numbers — everything is agreed on by both people.

### 📊 4. Dashboard & Reports
- **Overview** — total given, total borrowed, total interest earned/owed, total repayments, outstanding balances — all in one glance.
- Filter by **All / Given / Received** loans.
- **Parties view** — see totals grouped by each person or bank.
- **Sandbox / Copies** — create a "what-if" test copy of a loan to try out different scenarios without affecting your real numbers.
- **Activity Log** — a timestamped history of everything: loans created, payments added, connections made, loans closed.
- Switch between **List view** and **Grid view** for browsing your loans.

### 🌐 5. Multi-Currency Display
- Change the currency you view your amounts in (INR, USD, EUR, GBP, and more).
- Go to **Settings → Currency** and pick your preferred currency.
- Every amount across the app updates immediately — this only changes how numbers are *displayed*, your actual saved data stays consistent.

### 👤 6. Your Profile & Account
- **Signed in with Google?** Your name and profile photo are shown in Settings exactly as they appear on your Google account, and update automatically if you change them on Google. They can't be edited manually inside LoanBridge360.
- **Signed in with Email/Password?** Your profile shows your email as your display name.
- **Forgot your password?** Use the reset-password link on the sign-in screen — a reset email will be sent to you.
- **Delete your account** anytime from Settings — you get a **30-day grace period**, and if you log back in during that time, the deletion is automatically cancelled.

### 🎨 7. Look & Feel
- Toggle **Dark Mode / Light Mode** from Appearance settings.
- Everything updates **in real time** — if you or your connected partner makes a change on another device, you'll see it instantly without refreshing.
- Installable as a **PWA** on Android, iOS, and Desktop.

---

## 🧮 How Interest Is Calculated

LoanBridge360 calculates interest automatically, **every day**, so the numbers you see are always current.

| Type | How It Works |
|------|-------------|
| **Simple Interest** | Grows in a straight line — calculated only on the original principal, for the exact number of days passed. |
| **Compound Interest** | Calculated on the principal *plus* accumulated interest — grows faster over time based on your chosen monthly or yearly rate. |

- If a loan has **multiple disbursements (tranches)** or rate changes over time, LoanBridge360 tracks each portion separately and adds them together — always accurate, even for complex, long-running loans.
- Any payment recorded is applied to **outstanding interest first**, then to the remaining principal.

---

## 📋 Step-by-Step: How to Use Everything

### ➕ Adding a Loan
1. Click **Add New Entry** (or **Add Loan**) from your dashboard.
2. Pick the direction (Received / Gave).
3. Pick Bank or Person, and enter their name.
4. Enter the amount, interest rate, and whether it's yearly/monthly.
5. Pick the start date.
6. Choose Simple or Compound interest.
7. Click **Save Entry** — the dashboard updates automatically.

### 💸 Adding a Payment
1. Open the loan.
2. Click **Add Payment** and enter the amount and date.
3. If it's a shared loan, wait for the other person to **Verify** it from their Pending Verifications panel.

### 🤝 Sharing a Loan
1. Open the loan → **Connect**.
2. Send an invite by **email** to the other person.
3. Once they accept, you're both connected — same balance, same history.

### ✅ Closing a Loan
1. Open the fully-paid loan.
2. Click **Mark as Closed**.
3. Find it later under **Closed Loans** — reopen anytime if needed.

### ⚙️ Changing Settings
- **Currency / Theme**: available from the sidebar or Settings menu.
- **Name / Photo**: synced automatically from your Google account — no manual edit option.
- **Password**: Sign-in screen → "Forgot password?" or from Settings. (Not applicable if you signed in with Google only.)

### 🗑️ Deleting Your Account
1. Settings → **Delete Account**.
2. Read the warning, click **I Understand, Continue**.
3. Enter your password to confirm.
4. Your account is scheduled for deletion in **30 days**. Log in anytime before then to cancel it automatically.

---

## ⚠️ Important Things to Know

- **🖥️ Use the Desktop version for the best experience.** The site works on phones as a responsive web app, but is built and tested primarily for desktop browsers — for full functionality, use a laptop or computer. You can also **install it as a PWA** on mobile.

- **📧 Use a real, valid email — don't try fake/temporary emails.** (Only applies to Email/Password sign-up — Google Sign-In always uses your real Google account.)
  - Sign-up only accepts genuine email providers (Gmail, Yahoo, Outlook, iCloud, etc.).
  - If you try to sign up with a **fake, invalid, or disposable/temporary email**, you will be **blocked** and shown:
    > "Temporary or disposable email addresses are not allowed. Please use a real email address."
  - If this happens, **wait some time and try again later** using a real, working email address.

- **A payment isn't final until the other person verifies it** on a shared loan — this protects both sides from wrong entries.

- **Deleting your account is not instant** — you have a **30-day safety window**. Logging back in during that time cancels the deletion automatically and keeps all your data safe.

---

## ❓ FAQ / Troubleshooting

**Q: I signed up but didn't get a confirmation email.**
A: Check your spam/junk folder. Make sure you used a real, supported email provider. (Not applicable if you use Google Sign-In.)

**Q: It says my email isn't allowed / I'm blocked from signing up.**
A: You used a temporary/disposable or unsupported email domain. Use a real Gmail/Yahoo/Outlook/iCloud etc. address, or sign in with Google instead.

**Q: Can I edit a loan after creating it?**
A: Yes — open the loan and choose **Edit** to update the rate, dates, or other details at any time.

**Q: What happens if the other person rejects a payment?**
A: The payment is marked as rejected with their note explaining why, and it won't affect the balance until it's corrected and re-submitted.

**Q: Can I change my name or profile photo?**
A: Not inside the app. Your name/photo come directly from your Google account — update them on Google and they'll refresh here automatically the next time you sign in.

**Q: Why is my payment still showing "Pending"?**
A: It needs to be **verified by the other connected person** on that shared loan. Ask them to open the loan and verify it from **Settings → Pending Verifications**.

**Q: Is there a mobile app?**
A: LoanBridge360 works as a **responsive web app** — open it in your phone's browser for a full mobile-friendly experience. You can also **install it as a PWA** on Android, iOS, and Desktop.

**Q: Can I use LoanBridge360 without connecting with the other person?**
A: Absolutely — you can track any loan purely for your own records without inviting anyone.

**Q: I want to undo my account deletion.**
A: Just **log back in** before the 30 days are up — it cancels automatically.

---

## 🔒 Security & Privacy

Your data belongs to you.

- Every account only ever sees its **own loans** and the shared loans it has been **explicitly connected to**.
- Sign-in is handled securely through **Google or email/password** with encrypted storage.
- LoanBridge360 **never shows your data** to anyone you haven't shared it with.

---

Made with ❤️ by **[Harshank Patel](https://www.linkedin.com/in/patel-harshank)**.
