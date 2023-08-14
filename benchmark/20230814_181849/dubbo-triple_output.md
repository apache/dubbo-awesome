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
# Warmup Iteration   1: 1.025 ops/ms
# Warmup Iteration   2: 2.340 ops/ms
# Warmup Iteration   3: 4.936 ops/ms
Iteration   1: 5.606 ops/ms
Iteration   2: 5.627 ops/ms
Iteration   3: 5.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.704 ±(99.9%) 2.770 ops/ms [Average]
  (min, avg, max) = (5.606, 5.704, 5.879), stdev = 0.152
  CI (99.9%): [2.934, 8.474] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.430 ops/ms
# Warmup Iteration   2: 4.684 ops/ms
# Warmup Iteration   3: 5.850 ops/ms
Iteration   1: 5.937 ops/ms
Iteration   2: 6.075 ops/ms
Iteration   3: 6.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.018 ±(99.9%) 1.310 ops/ms [Average]
  (min, avg, max) = (5.937, 6.018, 6.075), stdev = 0.072
  CI (99.9%): [4.708, 7.328] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.646 ops/ms
# Warmup Iteration   2: 4.560 ops/ms
# Warmup Iteration   3: 5.605 ops/ms
Iteration   1: 5.531 ops/ms
Iteration   2: 5.586 ops/ms
Iteration   3: 5.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.597 ±(99.9%) 1.314 ops/ms [Average]
  (min, avg, max) = (5.531, 5.597, 5.674), stdev = 0.072
  CI (99.9%): [4.283, 6.911] (assumes normal distribution)


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
# Warmup Iteration   1: 1.431 ops/ms
# Warmup Iteration   2: 4.091 ops/ms
# Warmup Iteration   3: 4.934 ops/ms
Iteration   1: 4.898 ops/ms
Iteration   2: 4.932 ops/ms
Iteration   3: 4.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.915 ±(99.9%) 0.309 ops/ms [Average]
  (min, avg, max) = (4.898, 4.915, 4.932), stdev = 0.017
  CI (99.9%): [4.606, 5.224] (assumes normal distribution)


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
# Warmup Iteration   1: 19.673 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.248 ±(99.9%) 0.008 ms/op
Iteration   1: 5.710 ±(99.9%) 0.007 ms/op
Iteration   2: 5.725 ±(99.9%) 0.013 ms/op
Iteration   3: 5.435 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.623 ±(99.9%) 2.985 ms/op [Average]
  (min, avg, max) = (5.435, 5.623, 5.725), stdev = 0.164
  CI (99.9%): [2.639, 8.608] (assumes normal distribution)


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
# Warmup Iteration   1: 17.457 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.394 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.440 ±(99.9%) 0.008 ms/op
Iteration   1: 5.518 ±(99.9%) 0.007 ms/op
Iteration   2: 5.476 ±(99.9%) 0.008 ms/op
Iteration   3: 5.634 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.543 ±(99.9%) 1.488 ms/op [Average]
  (min, avg, max) = (5.476, 5.543, 5.634), stdev = 0.082
  CI (99.9%): [4.054, 7.031] (assumes normal distribution)


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
# Warmup Iteration   1: 17.729 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.903 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.609 ±(99.9%) 0.011 ms/op
Iteration   1: 5.667 ±(99.9%) 0.008 ms/op
Iteration   2: 5.434 ±(99.9%) 0.012 ms/op
Iteration   3: 5.697 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.599 ±(99.9%) 2.630 ms/op [Average]
  (min, avg, max) = (5.434, 5.599, 5.697), stdev = 0.144
  CI (99.9%): [2.969, 8.230] (assumes normal distribution)


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
# Warmup Iteration   1: 21.254 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 7.661 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.928 ±(99.9%) 0.008 ms/op
Iteration   1: 6.669 ±(99.9%) 0.013 ms/op
Iteration   2: 6.309 ±(99.9%) 0.014 ms/op
Iteration   3: 6.299 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.426 ±(99.9%) 3.845 ms/op [Average]
  (min, avg, max) = (6.299, 6.426, 6.669), stdev = 0.211
  CI (99.9%): [2.581, 10.271] (assumes normal distribution)


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
# Warmup Iteration   1: 18.535 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 7.695 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.105 ±(99.9%) 0.033 ms/op
Iteration   1: 5.720 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.351 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   7.643 ms/op
                 createUser·p0.95:   9.093 ms/op
                 createUser·p0.99:   12.173 ms/op
                 createUser·p0.999:  19.479 ms/op
                 createUser·p0.9999: 25.835 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   2: 5.894 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.907 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.979 ms/op
                 createUser·p0.95:   9.306 ms/op
                 createUser·p0.99:   13.255 ms/op
                 createUser·p0.999:  19.193 ms/op
                 createUser·p0.9999: 29.739 ms/op
                 createUser·p1.00:   32.539 ms/op

Iteration   3: 5.877 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.200 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.561 ms/op
                 createUser·p0.95:   8.897 ms/op
                 createUser·p0.99:   12.550 ms/op
                 createUser·p0.999:  30.528 ms/op
                 createUser·p0.9999: 34.472 ms/op
                 createUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164542
  mean =      5.829 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 61062 
    [ 5.000,  7.500) = 84799 
    [ 7.500, 10.000) = 13225 
    [10.000, 12.500) = 3642 
    [12.500, 15.000) = 1105 
    [15.000, 17.500) = 342 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.907 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.709 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     12.747 ms/op
     p(99.9000) =     22.282 ms/op
     p(99.9900) =     33.179 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 17.530 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.073 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.573 ±(99.9%) 0.022 ms/op
Iteration   1: 5.450 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   7.135 ms/op
                 existUser·p0.95:   8.118 ms/op
                 existUser·p0.99:   11.272 ms/op
                 existUser·p0.999:  14.915 ms/op
                 existUser·p0.9999: 24.060 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   2: 5.407 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.269 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   7.102 ms/op
                 existUser·p0.95:   7.930 ms/op
                 existUser·p0.99:   11.308 ms/op
                 existUser·p0.999:  25.952 ms/op
                 existUser·p0.9999: 29.709 ms/op
                 existUser·p1.00:   34.734 ms/op

Iteration   3: 5.515 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.980 ms/op
                 existUser·p0.95:   8.108 ms/op
                 existUser·p0.99:   12.698 ms/op
                 existUser·p0.999:  28.509 ms/op
                 existUser·p0.9999: 32.532 ms/op
                 existUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175849
  mean =      5.457 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 83088 
    [ 5.000,  7.500) = 79869 
    [ 7.500, 10.000) = 9623 
    [10.000, 12.500) = 1973 
    [12.500, 15.000) = 732 
    [15.000, 17.500) = 257 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.655 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     21.558 ms/op
     p(99.9900) =     30.966 ms/op
     p(99.9990) =     33.665 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 19.456 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 7.103 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.832 ±(99.9%) 0.023 ms/op
Iteration   1: 5.854 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.920 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   7.463 ms/op
                 getUser·p0.95:   8.765 ms/op
                 getUser·p0.99:   13.156 ms/op
                 getUser·p0.999:  19.746 ms/op
                 getUser·p0.9999: 29.705 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 5.965 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.855 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   7.774 ms/op
                 getUser·p0.95:   9.617 ms/op
                 getUser·p0.99:   14.500 ms/op
                 getUser·p0.999:  25.403 ms/op
                 getUser·p0.9999: 28.657 ms/op
                 getUser·p1.00:   29.688 ms/op

Iteration   3: 5.833 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.597 ms/op
                 getUser·p0.50:   5.464 ms/op
                 getUser·p0.90:   7.471 ms/op
                 getUser·p0.95:   8.520 ms/op
                 getUser·p0.99:   12.861 ms/op
                 getUser·p0.999:  27.981 ms/op
                 getUser·p0.9999: 38.504 ms/op
                 getUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163040
  mean =      5.884 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 50971 
    [ 5.000,  7.500) = 95389 
    [ 7.500, 10.000) = 11211 
    [10.000, 12.500) = 3121 
    [12.500, 15.000) = 1379 
    [15.000, 17.500) = 590 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.597 ms/op
     p(50.0000) =      5.480 ms/op
     p(90.0000) =      7.528 ms/op
     p(95.0000) =      8.929 ms/op
     p(99.0000) =     13.533 ms/op
     p(99.9000) =     23.983 ms/op
     p(99.9900) =     37.820 ms/op
     p(99.9990) =     38.698 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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
# Warmup Iteration   1: 21.049 ±(99.9%) 0.403 ms/op
# Warmup Iteration   2: 8.822 ±(99.9%) 0.076 ms/op
# Warmup Iteration   3: 6.946 ±(99.9%) 0.032 ms/op
Iteration   1: 6.574 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   10.142 ms/op
                 listUser·p0.99:   14.346 ms/op
                 listUser·p0.999:  24.052 ms/op
                 listUser·p0.9999: 27.656 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 6.676 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   8.405 ms/op
                 listUser·p0.95:   9.683 ms/op
                 listUser·p0.99:   13.369 ms/op
                 listUser·p0.999:  29.658 ms/op
                 listUser·p0.9999: 32.047 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   3: 6.688 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.859 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.651 ms/op
                 listUser·p0.95:   9.926 ms/op
                 listUser·p0.99:   14.601 ms/op
                 listUser·p0.999:  26.939 ms/op
                 listUser·p0.9999: 30.331 ms/op
                 listUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144421
  mean =      6.646 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 8880 
    [ 5.000,  7.500) = 108417 
    [ 7.500, 10.000) = 20103 
    [10.000, 12.500) = 4492 
    [12.500, 15.000) = 1433 
    [15.000, 17.500) = 630 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      6.185 ms/op
     p(90.0000) =      8.520 ms/op
     p(95.0000) =      9.929 ms/op
     p(99.0000) =     14.205 ms/op
     p(99.9000) =     26.935 ms/op
     p(99.9900) =     31.184 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.704 ± 2.770  ops/ms
ClientPb.existUser                       thrpt       3   6.018 ± 1.310  ops/ms
ClientPb.getUser                         thrpt       3   5.597 ± 1.314  ops/ms
ClientPb.listUser                        thrpt       3   4.915 ± 0.309  ops/ms
ClientPb.createUser                       avgt       3   5.623 ± 2.985   ms/op
ClientPb.existUser                        avgt       3   5.543 ± 1.488   ms/op
ClientPb.getUser                          avgt       3   5.599 ± 2.630   ms/op
ClientPb.listUser                         avgt       3   6.426 ± 3.845   ms/op
ClientPb.createUser                     sample  164542   5.829 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.907           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.709           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.110           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.747           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.282           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.179           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.669           ms/op
ClientPb.existUser                      sample  175849   5.457 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.655           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.071           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.070           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.036           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.747           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.558           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.966           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.734           ms/op
ClientPb.getUser                        sample  163040   5.884 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.480           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.929           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.533           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.983           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.820           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.863           ms/op
ClientPb.listUser                       sample  144421   6.646 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.282           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.929           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.205           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.935           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.184           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.030           ms/op
