- 👋 Hi, I’m @codetech12
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
codetech12/codetech12 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Try to find and import the setting.py config file
try:
    sys.path.append("/etc/ssh/")
    import settings
except ImportError:
    print("\n[!] ERROR #1-1: can't import /etc/ssh/settings.py.   Run:
%s\n" % ( os.path.abspath("./config/update-config.py" )))
   sys.exit()
   
