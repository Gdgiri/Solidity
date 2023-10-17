// SPDX-License-Identifier:MIT

pragma solidity ^0.8.0; 

contract First{

  /* variables
----------------------------------------------------------------------------------------------------------------------------------------------------
    uint num1=0; 
    unit=>we want to define only positive part

    int num=-2;int=>
     we able to declare positive and negative part 

    bool num=true/false 
    bool=>we want to declare this both only 

    bytes name="giri"
    bytes=>
    * it as only 1-32 bytes value
    * fixed size of character set  storing purpose it using. then it store less amount of storage compare to string

    string name="nandhini";
    string=> it is also like a bytes but it is dynamic storage.

    address owner=0x5B38Da6a701c568545dCfcB03FcB875f56beddC4;
    address=> it is used for store etherium storage purpose it used lot
    
    these are inbuild datatypes
---------------------------------------------------------------------------------------------------------------------------------------------------
 */

uint public num1=4;
int public num=-2;
bool public value=true;
bytes public name="Giridharan";
string public name2="Nandhini";
address public owner=0x5B38Da6a701c568545dCfcB03FcB875f56beddC4;

     
}



    int public maxVlaue=type(int).max;// interger maximum value is => 57896044618658097711785492504343953926634992332820282019728792003956564819967 
    int public minValue=type(int).min; // minimum vslue of inter is => -57896044618658097711785492504343953926634992332820282019728792003956564819968
     uint public maxValue=type(uint).max;// maximum value of uint value is => 115792089237316195423570985008687907853269984665640564039457584007913129639935
  uint public minValue=type(uint).min;// minimum value of uint value is => 0
