#  id="alert"><%= alert %></p>
<h1>Login</h1>
<%= form_tag sessions_path do |form| %>
<div class="field">
	<%= label_tag :email %>
	<%= text_field_tag :email %>
</div>
	<div class="field">
		<%= label_tag :password %>
		<%= password_field_tag :password %>
	</div>
	<div class="actions">
		<%= submit_tag "Login" %>
	</div>
<%end%>
