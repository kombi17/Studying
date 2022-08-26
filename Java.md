# JAVA

<details>
    <summary style="font-size : 20px;"><strong>  Q. OOP란?   </strong></summary></br>
   
    Object Oriented Programming, 이를 설명하기 위해서는 객체(Object)에 대해서 먼저 알아봐야 합니다. 
    객체(Object)란? 데이터의 분산을 막기 위해 데이터와 기능을 하나로 묶은 그룹을 말합니다. 
    객체 지향 프로그래밍(OOP)란? 컴퓨터 프로그램을 객체의 모임으로 보는 것으로
    처리 요청을 받은 객체는 그 안의 기능을 사용해 요청을 처리합니다. 
    특징으로는 캡슐화, 상속, 다형성, 추상화 등이 있고 코드의 재사용성이 높아 확장 및 유지보수가 용이합니다. 

</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. OOP의 4가지 특징(캡슐화, 상속, 다형성, 추상화)에 대해 설명하세요.  </strong></summary></br>
   
    추상화 : 구체적인 사물들의 공통적인 특징을 파악해서 이를 하나의 개념으로 다루는 것을 뜻합니다.   

    캡슐화 : 객체에 대한 관련 데이터들과 메서드를 하나로 묶어 외부에 노출되지 않도록 은닉하는 것으로, 정보 은닉을 목적으로 외부에 불필요한 정보 노출을 막는 것입니다. 
    캡슐화를 하면 객체의 사용자로부터 정보 은폐가 가능하며 객체를 포함한 정보의 손상과 오용을 막을 수 있습니다. 

    상속 : 기존의 클래스를 재사용하여 새로운 클래스를 작성하는 것입니다.
    코드의 재사용성을 높이고 중복을 제거하여 생산성을 향상시키고 보다 편하게 유지보수가 가능하다는 장점이 있습니다. 

    다형성 : 동일한 부모 클래스 타입을 상속 받은 후손 클래스 타입들을 부모 타입으로 처리하는 기술을 말합니다.
    다형성을 지원하기 위해서는 동적 바인딩이 필수입니다. 간단하게는 하나의 기능에 대해 각자의 방식으로 동작하는 것을 말합니다. 

    ** 동적 바인딩 : 부모 타입으로 참조되는 후손 객체의 오버라이딩 된 메서드에 적용되며, 컴파일 시 부모의 메서드를 정적 바인딩 해두었다가
    프로그램이 실행될 때 참조하는 후손의 오버라이딩 된 메서드로 연결을 바꾸어 실행하는 것을 말합니다. 

</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. 자바의 기본형 데이터 타입과 참조형 데이터 타입에 대해 설명하시오.    </strong></summary></br>
    
    자바의 기본형 데이터 타입에는 논리형 boolean(1), 문자형 char(2), 정수형 byte(1), short(2), int(4), long(8), 실수형 float(4), double(8)이 있습니다. 
    참조형 데이터 타입은 객체의 주소를 저장하고 참조하는 타입으로 클래스, 배열 등이 이에 해당합니다. 

</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. 클래스와 객체에 대해 설명하시오.   </strong></summary></br>
    
    클래스는 객체를 만들어내기 위한 설계도 혹은 틀입니다. 객체를 생성할 때 사용합니다. 
    객체는 클래스를 기반으로 생성되며 자신의 고유 이름과 상태(field), 행동(method)를 갖습니다. 
    객체에 메모리가 할당되어 실제로 활용되는 실체를 인스턴스(instance)라고 부릅니다. 
    
</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. 추상클래스와 인터페이스의 차이점에 대해 설명하시오.   </strong></summary></br>
    
    추상클래스 : 클래스 내 추상 메서드가 하나 이상 포함되거나 abstract로 정의된 경우
    인터페이스(interface) : 모든 메서드가 추상 메서드로만 이루어진 경우
    
    인터페이스는 다중 상속이 가능하고 그 인터페이스를 구현하는 모든 클래스가 특정한 메서드를 반드시 갖도록 강제합니다. 
    추상클래스는 다중 상속이 불가능하고 상속 받는 클래스들의 공통적인 로직을 추상화하고 기능 확장을 위해 사용됩니다. 
    
</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. 제네릭(Generic)이란?   </strong></summary></br>
    
    클래스 내부에서 사용할 데이터 타입을 인스턴스가 생성될 때 확정하는 것입니다.
    
</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. 생성자(Constructor)에 대해 설명하시오.   </strong></summary></br>
    
    생성자는클래스와 같은 이름의 메서드로, 객체가 생성될 때 호출되는 메서드입니다. 
    파라미터를 다르게 하여 오버로딩 할 수 있습니다. 
    
</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. 오버로딩(overloading)과 오버라이딩(overriding)의 차이점에 대해 설명하시오.   </strong></summary></br>
    
    오버로딩 : 하나의 클래스 안에서 매개변수의 타입이나 갯수를 다르게 하여 같은 이름의 메서드를 여러 개 재정의 하는 것입니다. 
    오버라이딩 : 상위 클래스에 있는 메서드를 하위 클래스에서 재정의 하는 것을 뜻합니다.
    접근제한자를 상위 클래스와 같거나 넓은 범위로 변경이 가능합니다. 
    메서드 이름, 매개변수 갯수/타입/순서, 리턴 타입이 동일해야 합니다. 
    
</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. 접근제한자에 대해 설명하시오.   </strong></summary></br>
    
    변수 또는 메서드의 접근 범위를 설정하기 위해 사용하는 자바의 예약어로 public, protected, (default), private이 있습니다. 
    public : 접근 제한이 없습니다. 즉, 같은 프로젝트 내에서 어디서든 사용이 가능합니다.
    protected : 해당 패키지 내, 상속 받은 하위 클래스에서 접근이 가능합니다. 
    (default) : 해당 패키지 내에서만 접근이 가능합니다. 
    private : 해당 클래스에서만 접근이 가능합니다. 
    
</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. static 에 대해 설명하시오.   </strong></summary></br>
    
    추후 정리하여 추가 예정
    
</details></br>

<details>
    <summary style="font-size : 20px;"><strong>  Q. 자바의 메모리 영역에 대해 설명하시오.  </strong></summary></br>
    
    크게 세 영역으로 나뉘고 데이터 타입에 따라 할당됩니다. 
    메서드(Method) 영역 : 전역 변수와 static 변수를 저장하며 프로그램의 시작부터 종료까지 메모리에 남아있습니다.
    스택(Stack) 영역 : 지역변수와 매개변수, 리턴 값 등이 생성되는 영역입니다. 
    힙(Heap) 영역 : new 연산자를 통해 생성되는 객체(인스턴스), 배열 등이 이 영역에 저장되며, 가비지 컬렉션에 의해 메모리가 관리됩니다. 
    
    
</details></br>
