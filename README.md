import 'package:flutter/material.dart';

void main(){
  runApp(MyApp());
}



 class MyApp extends StatelessWidget {
  @override
   Widget build(BuildContext context) {
    var questions = [
      'What\'s your favorite color?'
      'Whats\'s your favrite animal?',
    ];
     return MaterialApp(
       home: Scaffold(
         appBar: AppBar(
            title:Text('My First App'),
       ),
       body:Column(
         children: [
           widget(child: Text('The question!')),
           RaisedButton(child:Text('Answer 1'),onPressed: null)],
           RaisedButton(child:Text('Answer 2'),onPressed: null)],
           RaisedButton(child:Text('Answer 3'),onPressed: null)],
       ),
     ),
    );
  }
}



