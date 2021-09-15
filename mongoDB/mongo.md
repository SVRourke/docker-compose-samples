# create account for app
# mongo admin -u admin_user -p password
# use habits
# db.createUser({
#   user: "app",
#   pwd: "password666",
#   roles: [{role: "readWrite", db: "habits"}],
#   passwordDigestor: "server"
# })