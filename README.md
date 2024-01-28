# Laravel Live Chat Implementations
<hr>
<h3>Steps: </h3>
<ul>
<li>We will use laravel Chatify Package to implement the live chat </li>
<li>composer require munafio/chatify</li>
<li>php artisan chatify:install</li>
<li>php artisan migrate</li>
<h5>You must have Authorized user to chat with</h5>
<li>Install Laravel jetstream for authentication, you can use your own</li>
<li>composer require laravel/jetstream</li>
<li>php artisan jetstream:install livewire</li>
<li>npm install</li>
<li>npm run build</li>
<li>php artisan migrate</li>
<h5></h5>
<li>Register a new account and visti http://127.0.0.1:8000/chatify, you will get a messeging option with no internet connection</li>
<li>No, internet connection because we didn't add pusher yet</li>
<li>Create a pusher account from here <a href="https://pusher.com/docs/channels/using_channels/events/#triggering-client-events">Link</a></li>
<li>Sign up a new account</li>
<li>Create app with default</li>
<li>Go to app setting and Enable client events</li>
<li>Goto App Keys option and copy the credentials app_id, key, secret, cluster</li>
<li>Paste those to env</li>
<li>Done</li>
<li>Go to http://127.0.0.1:8000/chatify, you can able to search and send message to other user, if user for test got to another browser and register a user.</li>
<li>If you can't see image, just adjust app_url from env like this APP_URL=http://localhost:8000</li>

</ul>
