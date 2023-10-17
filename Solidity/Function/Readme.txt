// SPDX-License-Identifier:MIT

pragma solidity ^0.8.0; 

contract sample{

/* function identifier{} public view returns(){
    return name;}
*/

 string public constant name="Nandhini";

//  function fun() public view returns(string memory)
//  {
//      return name;
//  }

 function funn() public pure returns(string memory)
 /*
  * in this line we not declare only string.
  * we able to declare uint and int data type also. 
  * memory keyword were used only for string not for another.
  * we able to return array but it takes space in gas. so it is bad practise
 */
 {
     return name;
 }

 function foo()public pure returns(string memory){
     return "Nandhini";
 }


}