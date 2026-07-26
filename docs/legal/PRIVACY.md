# What we do with your data
We add a login system for a single purpole only. Saving choreographs directly to your browser simply isn't enough and this setup does not sync your choreographies across devices, so our login system makes sure that your work is not in any way lost or accidentally deleted.

## What we actually gather
To save and view your saved choreographs, we only gather two things for your account. The metadata you used to sign up (which is only your public profile data), and the saved file in our database. This setup ensures that your choreographs are shareable to others, while also keeping your data safe.


Though this may look like any other website to you, websites actually have two types! DirectCue is a static website (with an encrypted, safe backend API just for the database), while a majority of websites (that can secretly get data from you), uses dynamic websites. Static websites are more safer, and you can actually see this in action by taking a look in the repository.

You can check the source code to verify the security of DirectCue and its login system.

<hr>

# Our RTBF / Right To Be Forgotten Policy[^1]
You're in control, and we prioritize your data to be all yours. Following this, you always have the right to delete all your data from DirectCue.

Following EU policies, when finishing an account deletion, our database automatically wipes your data clean off[^2], following your saved choreographs aswell. If you logged in with Google, your OAuth token will also be revoked, cutting all ties from DirectCue to your account[^3]. (this follows email sign ups aswell)

Overall, you are the one in control of your data. We do not fabricate or change your data at all while it is in the database, and others can't do that aswell (except when our database provider encounters a breach or goes down) with the security of our database service.

If you have questions about your privacy and how we handle your data, please contact us at schtools.d808c7@gmail.com.

[^1]: https://gdpr.eu/right-to-be-forgotten/
[^2]: https://supabase.com/docs/guides/database/postgres/cascade-deletes
[^3]: https://developers.google.com/identity/protocols/oauth2/web-server#tokenrevoke
