# Email_testing_50


First step install imap package after npm install our package.json file

npm install imap

then replace your login details 

var imap = new Imap({
    user: '*** email id ***',
    password: '********',
    host: 'imap.gmail.com',
    port: 993,
    tls: true
});


it will console inbox 50 email 