#flashcards #Spring 
Data: 2023-08-14 13:47
Title: [[HandlerInterceptor]]
Alias:
Header:

Что такое [[HandlerInterceptor]]?::[[HandlerInterceptor]] – это интерфейс, который должен реализовывать перехватчики, работающие с отображением обработчика в фреймворке
<!--SR:!2023-10-29,7,330-->



Body:


#Spring 
Какие методы имеет интерфейс `HandlerInterceptor`?
!---
Ответ:
	- `public boolean preHandle(HttpServletRequest request, HttpServletResponse response, Object handler)`
	- `public void postHandle(HttpServletRequest request, HttpServletResponse response, Object handler, ModelAndView modelAndView)`
	- `public void afterCompletion(HttpServletRequest request, HttpServletResponse response, Object handler, Exception ex)`
<!--SR:!2023-11-04,10,392-->




Главы:
- [[public boolean preHandle()]]
- [[public void postHandle()]]
- [[public void afterCompletion()]]
- [[HandlerInterceptorAdapter]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
