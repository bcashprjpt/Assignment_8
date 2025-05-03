# Assignment_8
#
#
# Setting.py:-
# * Here i have joined base_dir with tempaltes by using this 'DIRS': [os.path.join(BASE_DIR, 'templates')],
# * Here login and logout redirect url as LOGIN_REDIRECT_URL  = 'home'   LOGOUT_REDIRECT_URL = 'login'
# 
# Urls.py :-
# * Here i have added admin url, app url, login url and logout url
# 
# App/url.py:-
# * Here i have added admin url, app url, login url ,logout url, base url, home url and register url
# 
# 
# View.py:-
# base(request):
# * This method is used to request the object of base.html
# 
# home(request):
# * This method is used to request the object of home.html
# 
# login_view(request):
# * This method is used to request post method.
# * it accept the user name and password from the user and check user is present or not. if the user is present it redirect to home page else move to the login page
# 
# 
# register.html:-
# * This html page is used display the registration form 
# 
# base.html:
# * This html page is used for the base of all the html page
# 
# home.html:-
# * This html page is display the home page 
# * if the user is valid then it will display the welcome (username)
# * else it will display to login and register by clicking on this button it will redirect to that partricular page
# 
# login.html:-
# * This html page is used to display the login page 
# * Here i have used the custom form design according to by desire








