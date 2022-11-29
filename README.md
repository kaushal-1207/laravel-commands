<!DOCTYPE html>
<html>
<head>
</head>
<body>
<h1>Laravel Useful Commands</h1>
 
 
<h4>1: controller</h4>
<pre> 
	  php artisan make:controller UserController 
	  php artisan make:controller UserController --resource  
	  php artisan make:controller UserController --api  
	  php artisan make:controller UserController --invokable 
	  php artisan make:controller UserController --model=Photo 
</pre> 

<h4>2: model </h4>
<pre> 
	php artisan make:model Photo
	php artisan make:model Photo --migration --controller --resource 
	php artisan make:model Photo -crm 
</pre> 

<h4>3: migration  </h4>
<pre> 
	php artisan make:migration create_Users_table 
	php artisan make:migration create_Users_table --create=Table  
	php artisan make:migration create_Users_table --table=Users 
</pre> 

<h4>4: seeder   </h4>
<pre> 
	php artisan make:seeder BooksTableSeeder 
</pre> 


<h4>5: request    </h4>
<pre> 
	php artisan make:request StoreBlogPost  
</pre> 

<h4>6: middleware     </h4>
<pre> 
	php artisan make:middleware IsAdmin   
</pre> 

<h4>7: policy      </h4>
<pre> 
	php artisan make:policy PostPolicy
	php artisan make:policy PostPolicy --model=Photo     
</pre> 

<h4>8: command       </h4>
<pre> 
	php artisan make:command SendEmails 
	php artisan make:command SendEmails --command=Command      
</pre> 

<h4>9: event        </h4>
<pre> 
	php artisan make:event OrderShipped     
</pre> 

<h4>10: job         </h4>
<pre> 
	php artisan make:job SendReminderEmail    
	php artisan make:job SendReminderEmail --sync 
</pre> 

<h4>11: listener          </h4>
<pre> 
	php artisan make:listener SendShipmentNotification     
	php artisan make:listener SendShipmentNotification --event=Event 
	php artisan make:listener SendShipmentNotification --queued 
</pre> 


<h4>12: mail           </h4>
<pre> 
	php artisan make:mail OrderShipped     
	php artisan make:mail OrderShipped --markdown  
	php artisan make:mail OrderShipped --force 
</pre> 

<h4>13: notification            </h4>
<pre> 
	php artisan make:notification InvoicePaid      
	php artisan make:notification InvoicePaid --markdown  
	php artisan make:notification InvoicePaid --force 
</pre> 

<h4>14: provider             </h4>
<pre> 
	php artisan make:provider DuskServiceProvider  
</pre>

<h4>15: test              </h4>
<pre> 
	php artisan make:test UserTest
	php artisan make:test UserTest --unit    
</pre> 

<h4>16: channel               </h4>
<pre> 
	php artisan make:channel OrderChannel  
</pre> 

<h4>17: exception                </h4>
<pre> 
	php artisan make:exception UserNotFoundException
	php artisan make:exception UserNotFoundException --render
	php artisan make:exception UserNotFoundException --report     
</pre> 

<h4>18: factory                 </h4>
<pre> 
	php artisan make:factory PostFactory 
	php artisan make:factory PostFactory --model=Post     
</pre> 

<h4>19: observer                  </h4>
<pre> 
	php artisan make:observer PostObserver  
	php artisan make:observer PostObserver --model=Post    
</pre> 

<h4>20: rule</h4>
<pre> 
	php artisan make:rule Uppercase 
</pre> 

<h4>21: resource</h4>
<pre> 
	php artisan make:resource PostResource
	php artisan make:resource PostResource --collection=Post  
</pre> 

<h4>22: Application overview</h4>
<pre> 
	php artisan about
	php artisan about --only=environment 
</pre>

<h4>23: Application maintenance mode</h4>
<pre> 
	php artisan down
	php artisan down --retry=60 (seconds)
	php artisan down --render="maintenance" (page)
	php artisan down --redirect=/
	php artisan down --secret="myapp"
	php artisan up
</pre>

<h1>Laravel Old Authentication (Artisan Command)</h1>
<p>composer create-project laravel/laravel my-app</p>
<p>php artisan make:auth</p>
<br>

<h1>Laravel New Authentication (Artisan Command)</h1>
<p>composer create-project laravel/laravel my-app</p>
<p>composer require laravel/ui</p> 
<p>composer require laravel/ui --dev</p>

<p> > php artisan ui --help </p>
<p>php artisan ui vue</p>
<p>php artisan ui react</p>
<p>php artisan ui bootstrap</p>

<p> > auth </p>
<p>php artisan ui vue --auth </p>
<p>php artisan ui react --auth</p>
<p>php artisan ui bootstrap --auth</p>

<p>> node</p>
<p>npm install</p>
<p>npm run dev</p>
<p>Compiling Assets (Mix)</p>
<p>npm run watch</p><br>
<p>Asset Bundling (Vite)</p>
<p>npm run build</p>
</body>
</html>
