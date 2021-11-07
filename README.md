# day15.0
import 'package:flutter/material.dart';
void main()=> runApp(MyApp());

class MyApp extends StatefulWidget{
  @override
  _MyAppState createState() =>_MyAppState();
}
class _MyAppState extends State <MyApp>{
  @override
  Widget build(BuildContext context){
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(title: Text("Flotter "),),
        body: Center(
          child: Column(
            children: <Widget>[
              Container(
                margin: EdgeInsets.all(40),
                child: FlatButton(
                  child: Text('Login',style: TextStyle(fontSize: 30.0),),
                  color: Colors.pink,
                  onPressed: (){},

                ),
              ),
        Container(
          margin: EdgeInsets.all(40),
          child: FlatButton(
            child: Text('facbook',style: TextStyle(fontSize: 30.0),),
            color: Colors.cyanAccent,
            onPressed: (){},
          ),
        ),
              Container(
                margin: EdgeInsets.all(40),
                child: FlatButton(
                  child: Text(' SureCash',style: TextStyle(fontSize: 30.0),),
                  color: Colors.blue,
                  onPressed: (){},
                ),
              ),
              Container(
                margin: EdgeInsets.all(40),
                child: FlatButton(
                  child: Text('WhatsAPP',style: TextStyle(fontSize: 30.0),),
                  color: Colors.deepOrange,
                  onPressed: (){},
                ),
              ),
              Container(
                margin: EdgeInsets.all(40),
                child: FlatButton(
                  child: Text('bkash',style: TextStyle(fontSize: 30.0),),
                  color: Colors.greenAccent,
                  onPressed: (){},
                ),
              ),
              Container(
                margin: EdgeInsets.all(40),
                child: FlatButton(
                  child: Text('Rocket',style: TextStyle(fontSize: 30.0),),
                  color: Colors.red,
                  onPressed: (){},
                ),
              ),
              Container(
                margin: EdgeInsets.all(40),
                child: ElevatedButton(
                  child: Text('Signup'),
                  style: ElevatedButton.styleFrom(
                    primary: Colors.amberAccent,
                    textStyle: TextStyle(fontSize: 30),
                    padding: EdgeInsets.all(30)
                  ),

                  onPressed: (){
                    print("Clicked");
                  },
                ),
              ),
            ],
          ),
        ),
        floatingActionButton: FloatingActionButton(
          child: Icon(Icons.navigation),
          backgroundColor: Colors.deepOrange,
          foregroundColor: Colors.amberAccent,
          onPressed: (){

          },
        ),
      ),
    );
  }
}
