# RegonAPI
#  **using**

public async get(NIP: string) {
		const service = new GusApiRegon(process.env.GUS_API_REGON)
		const result: GusApiRegonItemInterface = await service.search({ Nip: NIP })
    console.log('Result:', result)
}
    Where GUS_API_REGON - your api key which you take from official website after loggin in'g
    Nip is param of search(can be Krs, Krsy, Nip, Nipy, Regon, Regony14zn, Regony9zn)
    NIP is data by which you try to find info about company(for expl:6340131017)
    
#Why it's better?
IT'S TYPESCRIPT

