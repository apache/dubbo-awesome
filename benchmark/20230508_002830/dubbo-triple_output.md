# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.596 ops/ms
# Warmup Iteration   2: 6.492 ops/ms
# Warmup Iteration   3: 9.204 ops/ms
Iteration   1: 9.630 ops/ms
Iteration   2: 9.858 ops/ms
Iteration   3: 9.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.788 ±(99.9%) 2.508 ops/ms [Average]
  (min, avg, max) = (9.630, 9.788, 9.876), stdev = 0.137
  CI (99.9%): [7.280, 12.296] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.963 ops/ms
# Warmup Iteration   2: 9.631 ops/ms
# Warmup Iteration   3: 10.264 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.352 ops/ms
Iteration   3: 10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.508 ±(99.9%) 2.675 ops/ms [Average]
  (min, avg, max) = (10.352, 10.508, 10.643), stdev = 0.147
  CI (99.9%): [7.833, 13.184] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.415 ops/ms
# Warmup Iteration   2: 8.448 ops/ms
# Warmup Iteration   3: 9.598 ops/ms
Iteration   1: 10.056 ops/ms
Iteration   2: 10.151 ops/ms
Iteration   3: 9.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.960 ±(99.9%) 4.605 ops/ms [Average]
  (min, avg, max) = (9.674, 9.960, 10.151), stdev = 0.252
  CI (99.9%): [5.355, 14.565] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.664 ops/ms
# Warmup Iteration   2: 8.128 ops/ms
# Warmup Iteration   3: 8.689 ops/ms
Iteration   1: 8.757 ops/ms
Iteration   2: 8.596 ops/ms
Iteration   3: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.679 ±(99.9%) 1.468 ops/ms [Average]
  (min, avg, max) = (8.596, 8.679, 8.757), stdev = 0.080
  CI (99.9%): [7.211, 10.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.987 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.003 ms/op
Iteration   1: 3.154 ±(99.9%) 0.004 ms/op
Iteration   2: 3.137 ±(99.9%) 0.004 ms/op
Iteration   3: 3.167 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.153 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (3.137, 3.153, 3.167), stdev = 0.015
  CI (99.9%): [2.871, 3.435] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.497 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.002 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
Iteration   3: 2.981 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.037 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (2.981, 3.037, 3.119), stdev = 0.073
  CI (99.9%): [1.710, 4.364] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.698 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.003 ms/op
Iteration   1: 3.290 ±(99.9%) 0.006 ms/op
Iteration   2: 3.216 ±(99.9%) 0.004 ms/op
Iteration   3: 3.260 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.256 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (3.216, 3.256, 3.290), stdev = 0.037
  CI (99.9%): [2.576, 3.935] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.853 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.008 ms/op
Iteration   1: 3.661 ±(99.9%) 0.010 ms/op
Iteration   2: 3.810 ±(99.9%) 0.009 ms/op
Iteration   3: 3.789 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.753 ±(99.9%) 1.474 ms/op [Average]
  (min, avg, max) = (3.661, 3.753, 3.810), stdev = 0.081
  CI (99.9%): [2.279, 5.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.836 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.008 ms/op
Iteration   1: 3.291 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  11.676 ms/op
                 createUser·p0.9999: 19.230 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  13.041 ms/op
                 createUser·p0.9999: 22.407 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.473 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  15.712 ms/op
                 createUser·p0.9999: 21.033 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299286
  mean =      3.206 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21415 
    [ 2.500,  5.000) = 272655 
    [ 5.000,  7.500) = 4319 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     15.637 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.546 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.789 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
Iteration   1: 3.101 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  12.685 ms/op
                 existUser·p0.9999: 20.015 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.289 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  14.921 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   3: 3.093 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 21.310 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311608
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29366 
    [ 2.500,  5.000) = 278149 
    [ 5.000,  7.500) = 3322 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.248 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     13.966 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     21.993 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.689 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.008 ms/op
Iteration   1: 3.217 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  17.564 ms/op
                 getUser·p0.9999: 22.120 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.187 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  19.879 ms/op
                 getUser·p0.9999: 22.346 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   3: 3.271 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  9.522 ms/op
                 getUser·p0.9999: 19.052 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297671
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16808 
    [ 2.500,  5.000) = 273188 
    [ 5.000,  7.500) = 6747 
    [ 7.500, 10.000) = 477 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     21.897 ms/op
     p(99.9990) =     22.939 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.012 ms/op
Iteration   1: 3.956 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 22.082 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 3.747 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  13.083 ms/op
                 listUser·p0.9999: 14.369 ms/op
                 listUser·p1.00:   14.664 ms/op

Iteration   3: 3.715 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 21.686 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252466
  mean =      3.803 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 242005 
    [ 5.000,  7.500) = 8377 
    [ 7.500, 10.000) = 1366 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     14.181 ms/op
     p(99.9900) =     21.382 ms/op
     p(99.9990) =     22.936 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.788 ± 2.508  ops/ms
ClientPb.existUser                       thrpt       3  10.508 ± 2.675  ops/ms
ClientPb.getUser                         thrpt       3   9.960 ± 4.605  ops/ms
ClientPb.listUser                        thrpt       3   8.679 ± 1.468  ops/ms
ClientPb.createUser                       avgt       3   3.153 ± 0.282   ms/op
ClientPb.existUser                        avgt       3   3.037 ± 1.327   ms/op
ClientPb.getUser                          avgt       3   3.256 ± 0.680   ms/op
ClientPb.listUser                         avgt       3   3.753 ± 1.474   ms/op
ClientPb.createUser                     sample  299286   3.206 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.551           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.637           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.561           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.741           ms/op
ClientPb.existUser                      sample  311608   3.078 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.149           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.966           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.611           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.249           ms/op
ClientPb.getUser                        sample  297671   3.225 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.290           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.584           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.827           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.897           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.986           ms/op
ClientPb.listUser                       sample  252466   3.803 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.871           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.181           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.382           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.970           ms/op
