пример JSON с ответами некоего интернет-магазина
Задание на автоматизацию проверки ответа API от сервера.
Требования к ответу:
timestamp: int
referer: string (url)
location: string (url)
remoteHost: string
partyId: string
sessionId: string
pageViewId: string
eventType: string (itemBuyEvent или itemViewEvent)
item_id: string
item_price: int
item_url: string (url)
basket_price: string
detectedDuplicate: bool
detectedCorruption: bool
firstInSession: bool
userAgentName: string
