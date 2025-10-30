<% configRef "..\\configs\\view\\format_net.yml" %>
<% set "Operation" (capitalize (get "operation")) %>
<% set "Fileformat" (capitalize (get "fileformat")) %>
<% set "FILEFORMAT" (upper (get "fileformat")) %>
<% set "fileformat" (lower (get "fileformat")) %>
<% set "ProductName" (dict "products.{product}.name") %>
<% set "ProductFullName" (dict "products.{product}.fullName") %>
<% set "ProductCode" (dict "products.{product}.code") %>
<% set "ProductUrl" (dict "products.{product}.url") %>
<% set "ProgLang" (dict "products.{product}.progLang") %>
<% set "PROGLANG" (dict "products.{product}.progLang") %>
<% set "SrcFileExt" (dict "products.{product}.srcFileExt") %>
<% set "DevEnv" (dict "products.{product}.devEnv") %>
<% set "Runtime" (dict "products.{product}.runtime") %>
<% set "RepoName" (dict "products.{product}.repoName") %>
<% set "RepoUrl" (dict "products.{product}.repoUrl") %>
<% set "ExampleFileExt" (get "fileformat") %>
<% set "OnlineAppPath" (lower (get "fileformat")) %>
<% set "OnlineAppLang" (cond (eq (get "lang") "no") "nb" (get "lang")) %>
<% include "..\\landings\\view\\_format_net.md" %>