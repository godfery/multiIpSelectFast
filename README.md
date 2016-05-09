# multiIpSelectFast

first #import "IpManage.h"
second add the code:
 NSMutableArray* tt = [[NSMutableArray alloc]init];
    
    [tt addObject:@"50.22.62.66"];
    [tt addObject:@"www.baidu.com"];
    [tt addObject:@"google.com"];
    [tt addObject:@"192.168.100.1"];
    [tt addObject:@"192.168.6.1"];    
//
    [[IpManage getInstance]init:tt];
    [[IpManage getInstance]do];

last 

IpManage.h voteIp is the fastest ip.


