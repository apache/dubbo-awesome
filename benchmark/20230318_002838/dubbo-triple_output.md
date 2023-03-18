# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.258 ops/ms
# Warmup Iteration   2: 2.910 ops/ms
# Warmup Iteration   3: 6.090 ops/ms
Iteration   1: 6.054 ops/ms
Iteration   2: 6.057 ops/ms
Iteration   3: 5.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.972 ±(99.9%) 2.627 ops/ms [Average]
  (min, avg, max) = (5.806, 5.972, 6.057), stdev = 0.144
  CI (99.9%): [3.345, 8.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.894 ops/ms
# Warmup Iteration   2: 5.612 ops/ms
# Warmup Iteration   3: 6.534 ops/ms
Iteration   1: 6.529 ops/ms
Iteration   2: 6.681 ops/ms
Iteration   3: 6.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.618 ±(99.9%) 1.440 ops/ms [Average]
  (min, avg, max) = (6.529, 6.618, 6.681), stdev = 0.079
  CI (99.9%): [5.178, 8.058] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.896 ops/ms
# Warmup Iteration   2: 5.212 ops/ms
# Warmup Iteration   3: 6.238 ops/ms
Iteration   1: 5.981 ops/ms
Iteration   2: 6.182 ops/ms
Iteration   3: 5.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.020 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (5.895, 6.020, 6.182), stdev = 0.147
  CI (99.9%): [3.330, 8.710] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.589 ops/ms
# Warmup Iteration   2: 4.090 ops/ms
# Warmup Iteration   3: 5.270 ops/ms
Iteration   1: 5.326 ops/ms
Iteration   2: 5.597 ops/ms
Iteration   3: 5.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.402 ±(99.9%) 3.109 ops/ms [Average]
  (min, avg, max) = (5.283, 5.402, 5.597), stdev = 0.170
  CI (99.9%): [2.293, 8.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 15.358 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.671 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.909 ±(99.9%) 0.006 ms/op
Iteration   1: 4.851 ±(99.9%) 0.010 ms/op
Iteration   2: 5.248 ±(99.9%) 0.007 ms/op
Iteration   3: 5.773 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.291 ±(99.9%) 8.438 ms/op [Average]
  (min, avg, max) = (4.851, 5.291, 5.773), stdev = 0.462
  CI (99.9%): [≈ 0, 13.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 14.597 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.292 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.132 ±(99.9%) 0.005 ms/op
Iteration   1: 4.779 ±(99.9%) 0.009 ms/op
Iteration   2: 4.801 ±(99.9%) 0.007 ms/op
Iteration   3: 4.892 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.824 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (4.779, 4.824, 4.892), stdev = 0.060
  CI (99.9%): [3.737, 5.912] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 16.125 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.632 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.788 ±(99.9%) 0.012 ms/op
Iteration   1: 4.944 ±(99.9%) 0.014 ms/op
Iteration   2: 4.697 ±(99.9%) 0.021 ms/op
Iteration   3: 5.287 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.976 ±(99.9%) 5.407 ms/op [Average]
  (min, avg, max) = (4.697, 4.976, 5.287), stdev = 0.296
  CI (99.9%): [≈ 0, 10.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 17.388 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.801 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.812 ±(99.9%) 0.015 ms/op
Iteration   1: 5.689 ±(99.9%) 0.015 ms/op
Iteration   2: 5.538 ±(99.9%) 0.012 ms/op
Iteration   3: 6.131 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.786 ±(99.9%) 5.614 ms/op [Average]
  (min, avg, max) = (5.538, 5.786, 6.131), stdev = 0.308
  CI (99.9%): [0.172, 11.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 16.291 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.508 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.456 ±(99.9%) 0.022 ms/op
Iteration   1: 4.951 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.950 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.095 ms/op
                 createUser·p0.95:   6.775 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  18.787 ms/op
                 createUser·p0.9999: 27.954 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   2: 4.808 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.101 ms/op
                 createUser·p0.50:   4.628 ms/op
                 createUser·p0.90:   5.906 ms/op
                 createUser·p0.95:   6.504 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  20.227 ms/op
                 createUser·p0.9999: 25.225 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   3: 5.068 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.159 ms/op
                 createUser·p0.50:   4.891 ms/op
                 createUser·p0.90:   6.152 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  30.793 ms/op
                 createUser·p0.9999: 35.239 ms/op
                 createUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 193957
  mean =      4.940 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 121153 
    [ 5.000,  7.500) = 68109 
    [ 7.500, 10.000) = 3629 
    [10.000, 12.500) = 631 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.676 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     35.939 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.555 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.636 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.852 ±(99.9%) 0.017 ms/op
Iteration   1: 4.790 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.989 ms/op
                 existUser·p0.50:   4.538 ms/op
                 existUser·p0.90:   6.013 ms/op
                 existUser·p0.95:   6.840 ms/op
                 existUser·p0.99:   8.831 ms/op
                 existUser·p0.999:  15.422 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   2: 4.558 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.331 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.226 ms/op
                 existUser·p0.99:   8.054 ms/op
                 existUser·p0.999:  16.870 ms/op
                 existUser·p0.9999: 21.758 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   3: 4.836 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   6.529 ms/op
                 existUser·p0.99:   8.962 ms/op
                 existUser·p0.999:  15.808 ms/op
                 existUser·p0.9999: 40.068 ms/op
                 existUser·p1.00:   42.336 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 202914
  mean =      4.725 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 150462 
    [ 5.000, 10.000) = 51390 
    [10.000, 15.000) = 824 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 125 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 11 
    [35.000, 40.000) = 45 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.968 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.586 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     38.123 ms/op
     p(99.9990) =     41.550 ms/op
     p(99.9999) =     42.336 ms/op
    p(100.0000) =     42.336 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.539 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 5.778 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.345 ±(99.9%) 0.018 ms/op
Iteration   1: 5.396 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.816 ms/op
                 getUser·p0.95:   8.307 ms/op
                 getUser·p0.99:   11.665 ms/op
                 getUser·p0.999:  27.735 ms/op
                 getUser·p0.9999: 35.460 ms/op
                 getUser·p1.00:   35.848 ms/op

Iteration   2: 5.085 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.318 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.135 ms/op
                 getUser·p0.99:   9.503 ms/op
                 getUser·p0.999:  23.052 ms/op
                 getUser·p0.9999: 28.489 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 4.982 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   5.783 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  22.342 ms/op
                 getUser·p0.9999: 29.770 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 186270
  mean =      5.148 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 104807 
    [ 5.000,  7.500) = 73849 
    [ 7.500, 10.000) = 5611 
    [10.000, 12.500) = 1305 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     24.213 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.439 ±(99.9%) 0.270 ms/op
# Warmup Iteration   2: 7.011 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.650 ±(99.9%) 0.021 ms/op
Iteration   1: 5.694 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.512 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  24.117 ms/op
                 listUser·p0.9999: 27.919 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 6.153 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   7.758 ms/op
                 listUser·p0.95:   9.241 ms/op
                 listUser·p0.99:   12.861 ms/op
                 listUser·p0.999:  28.053 ms/op
                 listUser·p0.9999: 31.603 ms/op
                 listUser·p1.00:   32.571 ms/op

Iteration   3: 5.604 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   6.627 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  18.349 ms/op
                 listUser·p0.9999: 20.859 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 165141
  mean =      5.807 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 36565 
    [ 5.000,  7.500) = 117056 
    [ 7.500, 10.000) = 8499 
    [10.000, 12.500) = 2092 
    [12.500, 15.000) = 480 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.066 ms/op
     p(50.0000) =      5.530 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      8.118 ms/op
     p(99.0000) =     11.026 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     29.343 ms/op
     p(99.9990) =     32.315 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.972 ± 2.627  ops/ms
ClientPb.existUser                       thrpt       3   6.618 ± 1.440  ops/ms
ClientPb.getUser                         thrpt       3   6.020 ± 2.690  ops/ms
ClientPb.listUser                        thrpt       3   5.402 ± 3.109  ops/ms
ClientPb.createUser                       avgt       3   5.291 ± 8.438   ms/op
ClientPb.existUser                        avgt       3   4.824 ± 1.087   ms/op
ClientPb.getUser                          avgt       3   4.976 ± 5.407   ms/op
ClientPb.listUser                         avgt       3   5.786 ± 5.614   ms/op
ClientPb.createUser                     sample  193957   4.940 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.950           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.751           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.676           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.077           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.398           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.603           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  202914   4.725 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.968           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.586           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.684           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.744           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.123           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.336           ms/op
ClientPb.getUser                        sample  186270   5.148 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.171           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.191           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.213           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.867           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.848           ms/op
ClientPb.listUser                       sample  165141   5.807 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.066           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.118           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.026           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.478           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.343           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.571           ms/op
