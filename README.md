自用的基于kaminari分页插件的模板
目前只有bootstrap(3)
git clone 以后把bootstrap目录cp到app/views/kaminari 之下
使用方法: <%= paginate @posts, theme: 'bootstrap' %>
