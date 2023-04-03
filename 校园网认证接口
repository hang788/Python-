import requests

# 校园网认证接口地址
url = 'http://172.17.6.1/'

# 填写您的账号和密码
username = ''
password = ''

# 构造认证请求
data = {
    'action': 'login',
    'username': username,
    'password': password,
    'ac_id': '1',
    'type': '1',
    'wbaredirect': '',
    'mac': '',
    'user_ip': '',
    'nas_ip': '',
    'pop': 'true',
    'is_ldap': '1',
    'local_auth': '1',
}

# 发送认证请求
response = requests.post(url, data=data)

# 查看认证结果
print(response.text)

