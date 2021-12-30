MODULE Module1
        CONST robtarget Bottom:=[[400,0,400],[0,0,1,0],[0,-1,0,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
    CONST robtarget Top:=[[1000,0,400],[0,0,1,0],[-1,0,-1,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
    CONST robtarget Home:=[[704.990919137,0,705.74730631],[0.190808996,0,0.981627183,0],[-1,0,-1,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
    CONST robtarget B_Right:=[[550,-259.807621135,400],[0,0.087155743,0.996194698,0],[-1,0,-1,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
    CONST robtarget T_Rigth:=[[850,-259.807621135,400],[0,-0.087155742,0.996194698,0],[-1,0,-1,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
    CONST robtarget T_Left:=[[850,259.807621135,400],[0,0.043619386,0.999048222,0],[0,-1,0,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
    CONST robtarget B_Left:=[[550,259.807621135,400],[0,-0.087155744,0.996194698,0],[0,-1,0,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
!***********************************************************
    !
    ! Module:  Module1
    !
    ! Description:
    !   <Insert description here>
    !
    ! Author: DHARANEESH
    !
    ! Version: 1.0
    !
    !***********************************************************
    
    
    !***********************************************************
    !
    ! Procedure main
    !
    !   This is the entry point of your program
    !
    !***********************************************************
    PROC main()
        !Add your code here
    ENDPROC
    PROC Path_10()
        MoveL Bottom,v1000,z100,MyTool\WObj:=wobj0;
        MoveC B_Right,T_Rigth,v1000,z100,MyTool\WObj:=wobj0;
        MoveC Top,T_Left,v1000,z100,MyTool\WObj:=wobj0;
        MoveC B_Left,Bottom,v1000,z100,MyTool\WObj:=wobj0;
        MoveL Home,v1000,z100,MyTool\WObj:=wobj0;
    ENDPROC
ENDMODULE