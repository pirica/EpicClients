# oceanPCGameClient


## Client Permissions
| Resource | Action |
| -------- | ------ |
| account:public:account | CREATE |
| account:public:account:externalAuthOnly | CREATE |
| catalog:shared:offers | READ |
| eulatracking:shared:agreementbyversion | READ |
| eulatracking:shared:latestagreement | READ |
| eulatracking:shared:responsehistory | READ |
| feedback:resource | ALL |
| imageservice | ALL |
| ocean:chatthreads:system | READ |
| ocean:cloudstorage:system | READ |
| ocean:cloudstorage:system:* | READ |
| social:activity:public | READ |
| social:groups:ns:ocean | READ |
| social:teams:ns:ocean | READ |
| xmpp:session:*:e7e9faff25a74d429eecbf3fae160abf | CREATE |
| xmpp:session:{xmpp.domain}:{accountId} | CREATE |

## Account Permissions
| Resource | Action |
| -------- | ------ |
| account:oauth:exchangeTokenCode | ALL |
| account:public:account | READ |
| account:public:account:* | READ |
| account:public:account:deviceAuths | CREATE READ DELETE |
| account:public:account:externalAuths | ALL |
| account:token:otherSessionsForAccountClient | DELETE |
| account:token:otherSessionsForAccountClientService | DELETE |
| blockList:{accountId} | READ UPDATE DELETE |
| communications:external:deregister:device | DELETE |
| communications:external:register:device | CREATE |
| eulatracking:public:displayagreement:{accountId} | READ |
| eulatracking:public:response:{accountId} | CREATE READ |
| friends:{accountId} | ALL |
| ocean:calendar | READ |
| ocean:chatthreads | ALL |
| ocean:chatthreads:system | READ |
| ocean:cloudstorage:system | READ |
| ocean:cloudstorage:system:* | READ |
| ocean:cloudstorage:user:{accountId} | ALL |
| ocean:cloudstorage:user:{accountId}:* | ALL |
| ocean:groups:*:admin | ALL |
| ocean:groups:*:member | ALL |
| ocean:matchmaking:session | READ |
| ocean:matchmaking:session:* | READ |
| ocean:matchmaking:session:*:invite | CREATE DELETE |
| ocean:matchmaking:session:*:join:{accountId} | CREATE |
| ocean:matchmaking:session:{accountId}:invite | READ |
| ocean:profile:user:{accountId}:commands | ALL |
| ocean:profile:{accountId}:grantaccess | ALL |
| ocean:profile:{accountId}:receipts | ALL |
| ocean:storefront | READ |
| priceengine:shared:offer:price | READ |
| social:activity:public | READ |
| social:groups:ns:ocean | READ UPDATE |
| social:party | ALL |
| xmpp:session:*:{accountId} | CREATE |

