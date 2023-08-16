# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.835 ops/ms
# Warmup Iteration   2: 4.072 ops/ms
# Warmup Iteration   3: 7.475 ops/ms
Iteration   1: 7.788 ops/ms
Iteration   2: 8.224 ops/ms
Iteration   3: 8.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.068 ±(99.9%) 4.445 ops/ms [Average]
  (min, avg, max) = (7.788, 8.068, 8.224), stdev = 0.244
  CI (99.9%): [3.623, 12.513] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.337 ops/ms
# Warmup Iteration   2: 6.979 ops/ms
# Warmup Iteration   3: 8.197 ops/ms
Iteration   1: 8.760 ops/ms
Iteration   2: 8.712 ops/ms
Iteration   3: 9.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.882 ±(99.9%) 4.624 ops/ms [Average]
  (min, avg, max) = (8.712, 8.882, 9.173), stdev = 0.253
  CI (99.9%): [4.258, 13.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.545 ops/ms
# Warmup Iteration   2: 7.231 ops/ms
# Warmup Iteration   3: 7.981 ops/ms
Iteration   1: 8.359 ops/ms
Iteration   2: 8.059 ops/ms
Iteration   3: 8.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.277 ±(99.9%) 3.477 ops/ms [Average]
  (min, avg, max) = (8.059, 8.277, 8.413), stdev = 0.191
  CI (99.9%): [4.800, 11.754] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.559 ops/ms
# Warmup Iteration   2: 6.079 ops/ms
# Warmup Iteration   3: 6.998 ops/ms
Iteration   1: 6.852 ops/ms
Iteration   2: 6.769 ops/ms
Iteration   3: 6.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.734 ±(99.9%) 2.529 ops/ms [Average]
  (min, avg, max) = (6.582, 6.734, 6.852), stdev = 0.139
  CI (99.9%): [4.206, 9.263] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.938 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.009 ms/op
Iteration   1: 3.839 ±(99.9%) 0.006 ms/op
Iteration   2: 3.742 ±(99.9%) 0.009 ms/op
Iteration   3: 3.698 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.760 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (3.698, 3.760, 3.839), stdev = 0.073
  CI (99.9%): [2.436, 5.083] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.987 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.005 ms/op
Iteration   1: 3.906 ±(99.9%) 0.005 ms/op
Iteration   2: 3.819 ±(99.9%) 0.008 ms/op
Iteration   3: 3.915 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.880 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.819, 3.880, 3.915), stdev = 0.053
  CI (99.9%): [2.909, 4.851] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.658 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.006 ms/op
Iteration   1: 4.118 ±(99.9%) 0.005 ms/op
Iteration   2: 3.930 ±(99.9%) 0.003 ms/op
Iteration   3: 4.034 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.027 ±(99.9%) 1.720 ms/op [Average]
  (min, avg, max) = (3.930, 4.027, 4.118), stdev = 0.094
  CI (99.9%): [2.308, 5.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.553 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.398 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.986 ±(99.9%) 0.014 ms/op
Iteration   1: 4.584 ±(99.9%) 0.009 ms/op
Iteration   2: 4.587 ±(99.9%) 0.012 ms/op
Iteration   3: 4.803 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.658 ±(99.9%) 2.287 ms/op [Average]
  (min, avg, max) = (4.584, 4.658, 4.803), stdev = 0.125
  CI (99.9%): [2.371, 6.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.336 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.016 ms/op
Iteration   1: 3.542 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  21.178 ms/op
                 createUser·p0.9999: 23.065 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   2: 3.671 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   7.392 ms/op
                 createUser·p0.999:  24.043 ms/op
                 createUser·p0.9999: 28.091 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 3.874 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  18.055 ms/op
                 createUser·p0.9999: 30.138 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 260241
  mean =      3.691 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4766 
    [ 2.500,  5.000) = 244993 
    [ 5.000,  7.500) = 8592 
    [ 7.500, 10.000) = 1114 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     19.606 ms/op
     p(99.9900) =     29.195 ms/op
     p(99.9990) =     30.500 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.405 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.512 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.012 ms/op
Iteration   1: 3.717 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   7.758 ms/op
                 existUser·p0.999:  21.393 ms/op
                 existUser·p0.9999: 25.834 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 3.996 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.534 ms/op
                 existUser·p0.999:  11.862 ms/op
                 existUser·p0.9999: 25.394 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.787 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.866 ms/op
                 existUser·p0.999:  13.684 ms/op
                 existUser·p0.9999: 42.963 ms/op
                 existUser·p1.00:   44.106 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250641
  mean =      3.830 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 236933 
    [ 5.000, 10.000) = 12942 
    [10.000, 15.000) = 528 
    [15.000, 20.000) = 14 
    [20.000, 25.000) = 133 
    [25.000, 30.000) = 56 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     41.087 ms/op
     p(99.9990) =     43.941 ms/op
     p(99.9999) =     44.106 ms/op
    p(100.0000) =     44.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.406 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 4.442 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.017 ms/op
Iteration   1: 3.887 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  12.878 ms/op
                 getUser·p0.9999: 20.071 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.942 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  20.311 ms/op
                 getUser·p0.9999: 22.967 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.911 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.645 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  13.730 ms/op
                 getUser·p0.9999: 25.422 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245414
  mean =      3.913 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1945 
    [ 2.500,  5.000) = 225825 
    [ 5.000,  7.500) = 15531 
    [ 7.500, 10.000) = 1406 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     24.770 ms/op
     p(99.9990) =     26.331 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.771 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.955 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.559 ±(99.9%) 0.017 ms/op
Iteration   1: 4.510 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  22.385 ms/op
                 listUser·p0.9999: 25.196 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 4.778 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.744 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 4.881 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.556 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 26.388 ms/op
                 listUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203202
  mean =      4.718 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 169704 
    [ 5.000,  7.500) = 26853 
    [ 7.500, 10.000) = 5025 
    [10.000, 12.500) = 937 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      2.200 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     18.710 ms/op
     p(99.9900) =     25.581 ms/op
     p(99.9990) =     26.832 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.068 ± 4.445  ops/ms
ClientPb.existUser                       thrpt       3   8.882 ± 4.624  ops/ms
ClientPb.getUser                         thrpt       3   8.277 ± 3.477  ops/ms
ClientPb.listUser                        thrpt       3   6.734 ± 2.529  ops/ms
ClientPb.createUser                       avgt       3   3.760 ± 1.324   ms/op
ClientPb.existUser                        avgt       3   3.880 ± 0.971   ms/op
ClientPb.getUser                          avgt       3   4.027 ± 1.720   ms/op
ClientPb.listUser                         avgt       3   4.658 ± 2.287   ms/op
ClientPb.createUser                     sample  260241   3.691 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.577           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.606           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.195           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.999           ms/op
ClientPb.existUser                      sample  250641   3.830 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.493           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.489           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.356           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.992           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.087           ms/op
ClientPb.existUser:existUser·p1.00      sample          44.106           ms/op
ClientPb.getUser                        sample  245414   3.913 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.944           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.423           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.209           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.697           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.770           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.673           ms/op
ClientPb.listUser                       sample  203202   4.718 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.200           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.267           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.455           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.710           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.581           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
