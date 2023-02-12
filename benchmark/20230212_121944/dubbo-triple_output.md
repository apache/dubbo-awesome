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
# Warmup Iteration   1: 2.607 ops/ms
# Warmup Iteration   2: 6.531 ops/ms
# Warmup Iteration   3: 9.606 ops/ms
Iteration   1: 9.626 ops/ms
Iteration   2: 9.891 ops/ms
Iteration   3: 9.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.725 ±(99.9%) 2.646 ops/ms [Average]
  (min, avg, max) = (9.626, 9.725, 9.891), stdev = 0.145
  CI (99.9%): [7.079, 12.371] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.697 ops/ms
# Warmup Iteration   2: 9.271 ops/ms
# Warmup Iteration   3: 10.520 ops/ms
Iteration   1: 10.453 ops/ms
Iteration   2: 10.893 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.718 ±(99.9%) 4.255 ops/ms [Average]
  (min, avg, max) = (10.453, 10.718, 10.893), stdev = 0.233
  CI (99.9%): [6.463, 14.973] (assumes normal distribution)


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
# Warmup Iteration   1: 3.762 ops/ms
# Warmup Iteration   2: 9.545 ops/ms
# Warmup Iteration   3: 9.327 ops/ms
Iteration   1: 10.159 ops/ms
Iteration   2: 9.851 ops/ms
Iteration   3: 10.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.118 ±(99.9%) 4.527 ops/ms [Average]
  (min, avg, max) = (9.851, 10.118, 10.342), stdev = 0.248
  CI (99.9%): [5.591, 14.644] (assumes normal distribution)


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
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 7.235 ops/ms
# Warmup Iteration   3: 8.348 ops/ms
Iteration   1: 8.599 ops/ms
Iteration   2: 8.621 ops/ms
Iteration   3: 8.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.689 ±(99.9%) 2.515 ops/ms [Average]
  (min, avg, max) = (8.599, 8.689, 8.848), stdev = 0.138
  CI (99.9%): [6.174, 11.205] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.722 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.401 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.006 ms/op
Iteration   1: 3.176 ±(99.9%) 0.007 ms/op
Iteration   2: 3.117 ±(99.9%) 0.005 ms/op
Iteration   3: 3.217 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.170 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (3.117, 3.170, 3.217), stdev = 0.051
  CI (99.9%): [2.247, 4.093] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.672 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.004 ms/op
Iteration   1: 3.157 ±(99.9%) 0.007 ms/op
Iteration   2: 3.184 ±(99.9%) 0.004 ms/op
Iteration   3: 3.241 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.194 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (3.157, 3.194, 3.241), stdev = 0.043
  CI (99.9%): [2.413, 3.975] (assumes normal distribution)


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
# Warmup Iteration   1: 8.211 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.005 ms/op
Iteration   1: 3.139 ±(99.9%) 0.001 ms/op
Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
Iteration   3: 3.122 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.122 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (3.105, 3.122, 3.139), stdev = 0.017
  CI (99.9%): [2.812, 3.433] (assumes normal distribution)


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
# Warmup Iteration   1: 8.064 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.005 ms/op
Iteration   1: 3.901 ±(99.9%) 0.005 ms/op
Iteration   2: 3.660 ±(99.9%) 0.009 ms/op
Iteration   3: 3.726 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.763 ±(99.9%) 2.271 ms/op [Average]
  (min, avg, max) = (3.660, 3.763, 3.901), stdev = 0.124
  CI (99.9%): [1.492, 6.033] (assumes normal distribution)


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
# Warmup Iteration   1: 8.118 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.009 ms/op
Iteration   1: 3.156 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  17.793 ms/op
                 createUser·p0.9999: 22.433 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.357 ms/op
                 createUser·p0.999:  10.823 ms/op
                 createUser·p0.9999: 29.087 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.283 ms/op
                 createUser·p0.999:  15.024 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302785
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26273 
    [ 2.500,  5.000) = 271050 
    [ 5.000,  7.500) = 4679 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     16.156 ms/op
     p(99.9900) =     28.148 ms/op
     p(99.9990) =     29.838 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.991 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
Iteration   1: 3.096 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  9.896 ms/op
                 existUser·p0.9999: 18.044 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   2: 3.138 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.393 ms/op
                 existUser·p0.999:  16.534 ms/op
                 existUser·p0.9999: 21.522 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  13.638 ms/op
                 existUser·p0.9999: 19.381 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310415
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24692 
    [ 2.500,  5.000) = 280798 
    [ 5.000,  7.500) = 4061 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     21.865 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.367 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.008 ms/op
Iteration   1: 3.271 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  15.990 ms/op
                 getUser·p0.9999: 17.939 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.280 ms/op
                 getUser·p0.999:  8.595 ms/op
                 getUser·p0.9999: 20.289 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  11.856 ms/op
                 getUser·p0.9999: 21.245 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293972
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22304 
    [ 2.500,  5.000) = 265191 
    [ 5.000,  7.500) = 5679 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     20.303 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 9.924 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.011 ms/op
Iteration   1: 3.808 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  15.699 ms/op
                 listUser·p0.9999: 23.384 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   2: 3.760 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  18.083 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   28.443 ms/op

Iteration   3: 3.802 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.439 ms/op
                 listUser·p0.9999: 14.788 ms/op
                 listUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253116
  mean =      3.790 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 244039 
    [ 5.000,  7.500) = 7081 
    [ 7.500, 10.000) = 1329 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.725 ± 2.646  ops/ms
ClientPb.existUser                       thrpt       3  10.718 ± 4.255  ops/ms
ClientPb.getUser                         thrpt       3  10.118 ± 4.527  ops/ms
ClientPb.listUser                        thrpt       3   8.689 ± 2.515  ops/ms
ClientPb.createUser                       avgt       3   3.170 ± 0.923   ms/op
ClientPb.existUser                        avgt       3   3.194 ± 0.781   ms/op
ClientPb.getUser                          avgt       3   3.122 ± 0.310   ms/op
ClientPb.listUser                         avgt       3   3.763 ± 2.271   ms/op
ClientPb.createUser                     sample  302785   3.169 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.687           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.156           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.148           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.638           ms/op
ClientPb.existUser                      sample  310415   3.090 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.010           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.860           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.087           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.265           ms/op
ClientPb.getUser                        sample  293972   3.263 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.083           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.090           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.303           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.627           ms/op
ClientPb.listUser                       sample  253116   3.790 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.411           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.364           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.443           ms/op
