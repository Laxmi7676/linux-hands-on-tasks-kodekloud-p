Step 1️⃣ SSH to App Server 1
ssh rose@stapp01

(or use the server user given in the lab, like tony, steve, etc.)

Step 2️⃣ Create the user rose without home directory
sudo useradd -M rose
Step 3️⃣ Verify the user
id rose

or

cat /etc/passwd | grep rose

✅ Final command (copy this):

sudo useradd -M rose
