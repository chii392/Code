1.这不是问题，只是提醒提醒更新 Moodle 版本FutureWarning: torch.utils._pytree._register_pytree_node已弃用。请改用torch.utils._pytree.register_pytree_node。_torch_pytree._register_pytree_node(
2.若您收到错误：mysql.connector.errors.DatabaseError->2003 (HY000): 无法连接到 '185.31.40.40:3306' 上的 MySQL 服务器（10060），
解决方案如下：请断开学校校园网（如 eduroam 等）的连接，因为学校网络对 POST 端口有特定加密限制。您可以使用手机热点或其他网络进行连接。
3.若遇到 numpy 相关问题，请安装 2.0 以下版本，因为其他一些模块（如 transforms）目前可能与最新版本不兼容。
4.若遇到 'en_core_web_sm' 相关问题，可通过以下链接下载->https://objects.githubusercontent.com/github-production-release-asset-2e65be/84940268/15132ab6-4050-4914-8fe8-ac2c2fdcb9cf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=releaseassetproduction%2F20241205%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241205T011235Z&X-Amz-Expires=300&X-Amz-Signature=d16187c591ff4e55aadb148840551810ff766ad1efe30908ec6ca8d698d0be26&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%3Den_core_web_sm-3.8.0-py3-none-any.whl&response-content-type=application%2Foctet-stream

或者您也可以通过以下方式导入，同样可行->import spacyspacy.cli.download ("en_core_web_sm")nlp = spacy.load ("en_core_web_sm")
