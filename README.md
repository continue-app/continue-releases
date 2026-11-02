# continue-releases

Continue is a Windows app for people who open the same set of things for each kind of work: a game server, a project, a study session. Create a profile with its apps, files, folders and links, and start them all at once, in the order you choose. When you finish, Continue asks whether you want to pick up where you left off next time. Your profiles and saved session live in your account, so you can resume them on another PC. Continue is honest about what it knows: it reports only what it has verified, and it does not promise to restore unsaved documents, browser tabs or game state.

**Windows may show a warning when you install this.** Windows says "Windows protected your PC" (SmartScreen) for programs from a publisher it does not know yet. Continue is not code-signed yet, because a signing certificate costs money. The warning does not mean something is wrong with the file, and it usually goes away as more people install the app.

To continue: click **More info**, then **Run anyway**.

**What you can check yourself**
- Continue installs for your own Windows user only. It does not ask for administrator rights and does not change system settings.
- It only opens the apps, files, folders and links you put in a profile, and it says what it could and could not verify.
- Check that the file is the one published here. In PowerShell or Command Prompt, run `certutil -hashfile Continue-Setup-X.Y.Z.exe SHA512` in the folder with the download. The result must be:

You can remove it any time under Settings > Apps. Your profiles stay in your account.
