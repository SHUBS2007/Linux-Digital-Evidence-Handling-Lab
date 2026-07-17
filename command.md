# Commands Used

## Navigation

```bash
pwd
ls
cd
```

---

## Directory Creation

```bash
mkdir Evidence Logs Reports Backup
```

---

## File Creation

```bash
touch chat.txt
touch password.txt
touch suspicious_ip.txt
```

---

## Editing Files

```bash
nano chat.txt
nano password.txt
nano suspicious_ip.txt
```

---

## Reading Files

```bash
cat chat.txt
cat password.txt
cat suspicious_ip.txt
```

---

## Finding Files

```bash
find . -name "chat.txt"
```

---

## Searching Evidence

```bash
grep "Delete" Evidence/chat.txt
```

---

## File Permissions

```bash
chmod 400 Evidence/chat.txt
```

---

## Backup

```bash
cp Evidence/chat.txt Backup/
```

---

## Rename

```bash
mv Evidence/password.txt Evidence/recovered_passwords.txt
```

---

## Archive

```bash
tar -czvf evidence_backup.tar.gz Evidence/
```

---

## Integrity Verification

```bash
sha256sum Evidence/chat.txt
```
