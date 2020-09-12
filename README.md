## 이더리움 2.0 과 확장성

> 이더리움 2.0 은 기존 이더리움 1.0 이 가지고 있던 여러 문제점들을 해결해 줄 것으로 기대를 모으고 있다.  먼저 평균 15 TPS 정도에 불과한 처리 용량을 대포 향상시킬 수 있을 것으로 기대된다.
> PoS 합의 알고리즘의 적용으로 기존 PoW 대비 빠른 블록 생성이 가능해 지며, 샤딩을 적용하여 기존 이더리움 1.0 에서
> 전체 노드가 참여하던 블록 검증 작업을 샤드 단위로 분산하여 처리하므로써 트랜잭션 처리 용량의 개선을 이루어 낼 수 있을
> 것으로 보인다. 이와 함께 영지식 증명(ZK-SNARK) 기술을 통해 트랜잭션의 익명성 보장이 가능해짐으로써 프라이버시를 강화 할 수 있을 것으로 보인다.

### 합의 알고리즘

> 블록체인의 합의 알고리즘은 분산된 노드에서 발생한 트랜잭션의 처리 순서를 결정하여 각각의 노드의 상태가 파편화 되지 않고 전체
> 블록체인이 하나의 Global State 를 유지할 수 있게 해주는 역할을 한다. 
> 이더리움 1.0 은 PoW 방식의 합의 알고리즘을 사용한다. 비트코인에 처음 적용된 PoW 방식의 합의 알고리즘은 지속적으로 합의를 이루어내어 블럭을 생산해 낼 수 있으며 누구나 블록체인 네트워크에 참여해 블록을 생산할 수 있는 공정한 기회가 주워진다는 장점을 가지고 있다. 
> 하지만 이러한 장점에도 불구하고 블록 생성을 위한 작업 증명 과정에 과도한 자원의 소비를 필요로 하며 생성된 블록의 확정에 오랜 시간이 소요되고 소위 'Mining Farm' 으로 불리는 전문 채굴 업체 등의 등장으로 공정한 블록 생산 기회가 사라지는 등 의 문제점을 드러내게 되었다. 이러한 문제들을 해결하기 위해서 이더리움 2.0 은 PoS 방식의 합의 알고리즘 도입을 결정하였다.
> Casper 로 명명된 이더리움 2.0 의 합의 알고리즘은 

 - PoW(작업증명)
 - PoS (지분증명)
	 - Casper
- PoA (권한증명)

### 대용량 블록체인 트랜잭션 처리
- 샤딩

### 이더리움 트랜잭션 파리이버시 보장
- ZK-Snark
- 영지시 증명(ZKP, Zero-knowlege Proofs)
