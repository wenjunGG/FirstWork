# FirstWork
fasdasdasasirst create ,may be try

alskjdlkasdlkasjlkdlaskdjlk

wyao ss

asdsa


db998245-2f72-4962-81ed-83e9485c3a80



import Json from '../Json' //测试用数据

export default {
	getTestData(key) {
		return Json[key];
	},
	//时间转换
	changeTime(date){
		let da=new Date(date)
		let year=da.getFullYear();
		let month=da.getMonth()+1;
		let day=da.getDate();
		let hour=da.getHours();
		let minutes=da.getMinutes();
		return year+'-'+(month<10?'0'+ month:month)+'-'+(day<10?'0'+day:day)
		+' '+(hour<10?'0'+hour:hour)
		+':'
		+(minutes<10?'0'+minutes:minutes);
	},
	//时间转换
	changedate(date){
		let da=new Date(date)
		let year=da.getFullYear();
		let month=da.getMonth()+1;
		let day=da.getDate();
		let hour=da.getHours();
		let minutes=da.getMinutes();
		return year+'-'+(month<10?'0'+ month:month)+'-'+(day<10?'0'+day:day);
	}
}

