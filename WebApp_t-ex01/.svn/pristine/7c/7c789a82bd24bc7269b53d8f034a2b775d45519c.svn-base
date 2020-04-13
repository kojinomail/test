<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ page import = "model.UserBean" %>
 <%	//セッションスコープからユーザー情報を取得
	UserBean loginUser = (UserBean)session.getAttribute("user");
%>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>ヘッダー</title>
</head>
<body>
<p>ログインユーザー：<%= loginUser.getId() %></p>
</body>
</html>