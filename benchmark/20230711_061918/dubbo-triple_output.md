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
# Warmup Iteration   1: 2.619 ops/ms
# Warmup Iteration   2: 6.638 ops/ms
# Warmup Iteration   3: 9.271 ops/ms
Iteration   1: 9.997 ops/ms
Iteration   2: 10.206 ops/ms
Iteration   3: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.931 ±(99.9%) 5.721 ops/ms [Average]
  (min, avg, max) = (9.590, 9.931, 10.206), stdev = 0.314
  CI (99.9%): [4.210, 15.652] (assumes normal distribution)


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
# Warmup Iteration   1: 3.707 ops/ms
# Warmup Iteration   2: 9.235 ops/ms
# Warmup Iteration   3: 10.069 ops/ms
Iteration   1: 10.117 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.336 ±(99.9%) 5.093 ops/ms [Average]
  (min, avg, max) = (10.117, 10.336, 10.651), stdev = 0.279
  CI (99.9%): [5.243, 15.429] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.645 ops/ms
# Warmup Iteration   2: 9.145 ops/ms
# Warmup Iteration   3: 9.722 ops/ms
Iteration   1: 10.055 ops/ms
Iteration   2: 10.201 ops/ms
Iteration   3: 9.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.056 ±(99.9%) 2.650 ops/ms [Average]
  (min, avg, max) = (9.911, 10.056, 10.201), stdev = 0.145
  CI (99.9%): [7.405, 12.706] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.888 ops/ms
# Warmup Iteration   2: 7.329 ops/ms
# Warmup Iteration   3: 8.410 ops/ms
Iteration   1: 8.382 ops/ms
Iteration   2: 8.671 ops/ms
Iteration   3: 8.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.576 ±(99.9%) 3.067 ops/ms [Average]
  (min, avg, max) = (8.382, 8.576, 8.676), stdev = 0.168
  CI (99.9%): [5.510, 11.643] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.059 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.007 ms/op
Iteration   1: 3.319 ±(99.9%) 0.005 ms/op
Iteration   2: 3.185 ±(99.9%) 0.006 ms/op
Iteration   3: 3.171 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.225 ±(99.9%) 1.486 ms/op [Average]
  (min, avg, max) = (3.171, 3.225, 3.319), stdev = 0.081
  CI (99.9%): [1.739, 4.711] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.408 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.002 ms/op
Iteration   1: 3.000 ±(99.9%) 0.004 ms/op
Iteration   2: 3.149 ±(99.9%) 0.010 ms/op
Iteration   3: 3.145 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.098 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (3.000, 3.098, 3.149), stdev = 0.085
  CI (99.9%): [1.550, 4.646] (assumes normal distribution)


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
# Warmup Iteration   1: 8.742 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.003 ms/op
Iteration   1: 3.194 ±(99.9%) 0.004 ms/op
Iteration   2: 3.261 ±(99.9%) 0.004 ms/op
Iteration   3: 3.185 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.213 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (3.185, 3.213, 3.261), stdev = 0.041
  CI (99.9%): [2.462, 3.964] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.943 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.008 ms/op
Iteration   1: 3.673 ±(99.9%) 0.011 ms/op
Iteration   2: 3.782 ±(99.9%) 0.007 ms/op
Iteration   3: 3.693 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.716 ±(99.9%) 1.059 ms/op [Average]
  (min, avg, max) = (3.673, 3.716, 3.782), stdev = 0.058
  CI (99.9%): [2.656, 4.775] (assumes normal distribution)


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
# Warmup Iteration   1: 7.365 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
Iteration   1: 3.182 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  19.268 ms/op
                 createUser·p0.9999: 25.426 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 3.293 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  17.516 ms/op
                 createUser·p0.9999: 22.433 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 3.249 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  16.534 ms/op
                 createUser·p0.9999: 22.615 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296026
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18340 
    [ 2.500,  5.000) = 270374 
    [ 5.000,  7.500) = 6031 
    [ 7.500, 10.000) = 685 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     17.690 ms/op
     p(99.9900) =     24.229 ms/op
     p(99.9990) =     25.462 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.759 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.008 ms/op
Iteration   1: 3.162 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  14.396 ms/op
                 existUser·p0.9999: 20.902 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   2: 3.079 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  13.697 ms/op
                 existUser·p0.9999: 39.993 ms/op
                 existUser·p1.00:   41.091 ms/op

Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 21.045 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307423
  mean =      3.119 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 302382 
    [ 5.000, 10.000) = 4597 
    [10.000, 15.000) = 189 
    [15.000, 20.000) = 100 
    [20.000, 25.000) = 123 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     13.444 ms/op
     p(99.9900) =     38.503 ms/op
     p(99.9990) =     40.945 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


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
# Warmup Iteration   1: 7.845 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.010 ms/op
Iteration   1: 3.296 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  18.287 ms/op
                 getUser·p0.9999: 21.611 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   2: 3.354 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  18.724 ms/op
                 getUser·p0.9999: 22.427 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  16.106 ms/op
                 getUser·p0.9999: 24.579 ms/op
                 getUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285252
  mean =      3.362 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16860 
    [ 2.500,  5.000) = 257161 
    [ 5.000,  7.500) = 9981 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.484 ms/op
     p(99.9000) =     16.773 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     25.279 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 9.673 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.301 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.011 ms/op
Iteration   1: 3.765 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 22.102 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.681 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.710 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257015
  mean =      3.733 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 250035 
    [ 5.000,  7.500) = 5147 
    [ 7.500, 10.000) = 1082 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     20.771 ms/op
     p(99.9990) =     22.526 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.931 ± 5.721  ops/ms
ClientPb.existUser                       thrpt       3  10.336 ± 5.093  ops/ms
ClientPb.getUser                         thrpt       3  10.056 ± 2.650  ops/ms
ClientPb.listUser                        thrpt       3   8.576 ± 3.067  ops/ms
ClientPb.createUser                       avgt       3   3.225 ± 1.486   ms/op
ClientPb.existUser                        avgt       3   3.098 ± 1.548   ms/op
ClientPb.getUser                          avgt       3   3.213 ± 0.751   ms/op
ClientPb.listUser                         avgt       3   3.716 ± 1.059   ms/op
ClientPb.createUser                     sample  296026   3.241 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.871           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.690           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.229           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.494           ms/op
ClientPb.existUser                      sample  307423   3.119 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.094           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.444           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.503           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.091           ms/op
ClientPb.getUser                        sample  285252   3.362 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.733           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.484           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.773           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.167           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.411           ms/op
ClientPb.listUser                       sample  257015   3.733 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.436           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.771           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.544           ms/op
