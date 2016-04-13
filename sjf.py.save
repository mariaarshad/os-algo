
#include<stdio.h>
def main():
	info=[{'pn':'p1','AP':0,'BT':5},{'pn':'p2','AP':0,'BT':2},{'pn':'p3','AP':3,'BT':4}]
	if (info[0]['AP']== 0) and (info[1]['AP']!= 0) and( info[2]['AP'] != 0):
		info[0]['wt']=0
	
		print("Waiting time of",info[0]['pn'],"is",info[0]['wt']) 
		info[1]['wt']=info[0]['BT']-info[1]['AP']
		print("Waiting time of",info[1]['pn'],"is",info[1]['wt'])
		info[2]['wt']=info[0]['BT']+info[1]['BT']-info[2]['AP']
		print("Waiting time of",info[2]['pn'],"is",info[2]['wt'])
		print("AVG WAITING TIME IS",(info[0]['wt']+info[1]['wt']+info[2]['wt'])/3)
		print("TURN ARROUND time is",info[0]['BT']+info[1]['BT']+info[2]['BT'])

	elif((info[0]['AP']==info[1]['AP'])==0 and info[2]['AP'] ! =0):
		if(info[0]['BT']<info[1]['BT']):
			info[0]['wt']=0
			print("Waiting time of",info[0]['pn'],"is",info[0]['wt']) 
			info[1]['wt']=info[0]['BT']-info[1]['AP']
			print("Waiting time of",info[1]['pn'],"is",info[1]['wt'])
			info[2]['wt']=info[0]['BT']+info[1]['BT']-info[2]['AP']
			print("Waiting time of",info[2]['pn'],"is",info[2]['wt'])
			print("AVG WAITING TIME IS",(info[0]['wt']+info[1]['wt']+info[2]['wt'])/3)
			print("TURN ARROUND time is",info[0]['BT']+info[1]['BT']+info[2]['BT'])
		else:
			info[1]['wt']=0
	
			print("Waiting time of",info[1]['pn'],"is",info[1]['wt']) 
			info[0]['wt']=info[1]['BT']-info[0]['AP']
			print("Waiting time of",info[0]['pn'],"is",info[0]['wt'])
			info[2]['wt']=info[0]['BT']+info[1]['BT']-info[2]['AP']
			print("Waiting time of",info[2]['pn'],"is",info[2]['wt'])
			print("AVG WAITING TIME IS",(info[0]['wt']+info[1]['wt']+info[2]['wt'])/3)
			print("TURN ARROUND time is",info[0]['BT']+info[1]['BT']+info[2]['BT'])

	elif((info[0]['AP']==info[1]['AP']==info[2]['AP'])==0)
		if(info[0]['BT']<info[1]['BT'] and info[0]['BT']<info[2]['BT']):
			info[0]['wt']=0
			print("Waiting time of",info[0]['pn'],"is",info[0]['wt']) 
			info[1]['wt']=info[0]['BT']-info[1]['AP']
			print("Waiting time of",info[1]['pn'],"is",info[1]['wt'])
			info[2]['wt']=info[0]['BT']+info[1]['BT']-info[2]['AP']
			print("Waiting time of",info[2]['pn'],"is",info[2]['wt'])
			print("AVG WAITING TIME IS",(info[0]['wt']+info[1]['wt']+info[2]['wt'])/3)
			print("TURN ARROUND time is",info[0]['BT']+info[1]['BT']+info[2]['BT'])
		elif(info[1]['BT']<info[0]['BT'] and info[1]['BT']<info[2]['BT'])
			info[1]['wt']=0
	
			print("Waiting time of",info[1]['pn'],"is",info[1]['wt']) 
			info[0]['wt']=info[1]['BT']-info[0]['AP']
			print("Waiting time of",info[0]['pn'],"is",info[0]['wt'])
			info[2]['wt']=info[0]['BT']+info[1]['BT']-info[2]['AP']
			print("Waiting time of",info[2]['pn'],"is",info[2]['wt'])
			print("AVG WAITING TIME IS",(info[0]['wt']+info[1]['wt']+info[2]['wt'])/3)
			print("TURN ARROUND time is",info[0]['BT']+info[1]['BT']+info[2]['BT'])
		else
			info[2]['wt']=0
	
			print("Waiting time of",info[2]['pn'],"is",info[2]['wt']) 
			info[0]['wt']=info[2]['BT']-info[0]['AP']
			print("Waiting time of",info[0]['pn'],"is",info[0]['wt'])
			info[1]['wt']=info[0]['BT']+info[2]['BT']-info[1]['AP']
			print("Waiting time of",info[1]['pn'],"is",info[1]['wt'])
			print("AVG WAITING TIME IS",(info[0]['wt']+info[1]['wt']+info[2]['wt'])/3)
			print("TURN ARROUND time is",info[0]['BT']+info[1]['BT']+info[2]['BT'])

	
if __name__=="__main__":
	main() 


