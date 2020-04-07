For this tutorial, we'll be using the OpenShift web console.
Click on the _Console_ tab at the top of the dashboard to the right.

This will bring up the OpenShift login dialog.

![Web Console Login](./certifai-notebook/assets/01-web-console-login.png)

For the credentials, enter:

* **Username:** ``developer``{{copy}}
* **Password:** ``developer``{{copy}}

and click **Log In**

Now use the pulldown menu at the top left to switch from _Administrator_ to _Developer_.

![List of Projects](./certifai-notebook/assets/01-switch-to-developer.png)

You will see a _Restricted Access_ warning. Don't worry, that's expected.

![Restricted Access](./certifai-notebook/assets/01-restricted-access.png)

Using the _Project_ pulldown, set the project to _myproject_.

![Switch to Default](./certifai-notebook/assets/01-switch-from-default.png)

You should see a deployment object like this; click anywhere inside the blue ring to bring up a status display.

![Light Blue Deploy](./certifai-notebook/assets/01-light-blue-deploy.png)

When the application is fully deployed, the outer ring will turn dark blue
and the pod status in the display will say _Running_. When this happens,
you're ready to continue

![Dark Blue Deploy](./certifai-notebook/assets/01-dark-blue-with-running.png)
