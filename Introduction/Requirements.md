### 1. State
State는 React 컴포넌트의 상태를 저장하는 데이터입니다. 이 데이터는 사용자의 액션에 의해 변할 수 있으며, 변화가 발생하면 React가 컴포넌트를 리렌더링합니다.
클래스 컴포넌트에서는 this.state를 사용하여 state를 관리하고, this.setState() 메서드를 통해 state를 업데이트합니다.

### 2. Props
Props (Properties의 줄임말)는 부모 컴포넌트로부터 자식 컴포넌트로 전달되는 데이터입니다. 이 데이터는 컴포넌트가 외부에서 받아들이는 매개변수와 같으며, 일반적으로 변경되지 않습니다.
Props는 컴포넌트의 재사용성을 높이는 데 중요한 역할을 하며, 특정 컴포넌트가 다른 컴포넌트와 상호작용하는 방식을 정의하는 데 사용됩니다.

### 3. useState
useState는 함수형 컴포넌트에서 state를 관리하기 위한 Hook입니다. 이전의 클래스 컴포넌트에서만 사용 가능했던 state 기능을 함수형 컴포넌트에서도 사용할 수 있게 해줍니다.
useState는 현재 상태 값과 이 상태를 업데이트하는 함수를 쌍으로 제공합니다. 예를 들어, [count, setCount] = useState(0)는 count라는 상태 변수와 이 변수를 변경할 수 있는 setCount 함수를 생성합니다.

### 4. useEffect
useEffect는 함수형 컴포넌트에서 부수 효과(side effects)를 수행하기 위한 Hook입니다. 이는 데이터 가져오기, 구독 설정, 수동 DOM 조작 등 컴포넌트의 렌더링 결과에 영향을 미치는 작업을 수행할 때 사용됩니다.
useEffect는 컴포넌트가 렌더링될 때마다 특정 코드를 실행할 수 있게 해주며, 두 번째 인자로 배열을 전달하여 어떤 값이 변경되었을 때만 효과를 실행하도록 조절할 수 있습니다.