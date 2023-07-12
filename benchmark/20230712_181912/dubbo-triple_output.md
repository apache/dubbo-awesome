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
# Warmup Iteration   1: 1.521 ops/ms
# Warmup Iteration   2: 3.977 ops/ms
# Warmup Iteration   3: 6.675 ops/ms
Iteration   1: 7.054 ops/ms
Iteration   2: 7.385 ops/ms
Iteration   3: 7.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.197 ±(99.9%) 3.108 ops/ms [Average]
  (min, avg, max) = (7.054, 7.197, 7.385), stdev = 0.170
  CI (99.9%): [4.088, 10.305] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.270 ops/ms
# Warmup Iteration   2: 6.832 ops/ms
# Warmup Iteration   3: 7.396 ops/ms
Iteration   1: 7.796 ops/ms
Iteration   2: 7.788 ops/ms
Iteration   3: 7.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.721 ±(99.9%) 2.236 ops/ms [Average]
  (min, avg, max) = (7.580, 7.721, 7.796), stdev = 0.123
  CI (99.9%): [5.485, 9.957] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.631 ops/ms
# Warmup Iteration   2: 6.430 ops/ms
# Warmup Iteration   3: 6.987 ops/ms
Iteration   1: 7.271 ops/ms
Iteration   2: 7.406 ops/ms
Iteration   3: 7.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.246 ±(99.9%) 3.180 ops/ms [Average]
  (min, avg, max) = (7.061, 7.246, 7.406), stdev = 0.174
  CI (99.9%): [4.066, 10.426] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.235 ops/ms
# Warmup Iteration   2: 5.935 ops/ms
# Warmup Iteration   3: 5.907 ops/ms
Iteration   1: 6.366 ops/ms
Iteration   2: 6.354 ops/ms
Iteration   3: 6.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.333 ±(99.9%) 0.870 ops/ms [Average]
  (min, avg, max) = (6.278, 6.333, 6.366), stdev = 0.048
  CI (99.9%): [5.463, 7.203] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.817 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.158 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.603 ±(99.9%) 0.009 ms/op
Iteration   1: 4.458 ±(99.9%) 0.017 ms/op
Iteration   2: 4.406 ±(99.9%) 0.010 ms/op
Iteration   3: 4.485 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.449 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (4.406, 4.449, 4.485), stdev = 0.040
  CI (99.9%): [3.715, 5.184] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.395 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.706 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.420 ±(99.9%) 0.010 ms/op
Iteration   1: 4.282 ±(99.9%) 0.009 ms/op
Iteration   2: 4.163 ±(99.9%) 0.016 ms/op
Iteration   3: 4.344 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.263 ±(99.9%) 1.672 ms/op [Average]
  (min, avg, max) = (4.163, 4.263, 4.344), stdev = 0.092
  CI (99.9%): [2.591, 5.935] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.072 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.734 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.587 ±(99.9%) 0.007 ms/op
Iteration   1: 4.487 ±(99.9%) 0.010 ms/op
Iteration   2: 4.384 ±(99.9%) 0.010 ms/op
Iteration   3: 4.591 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.487 ±(99.9%) 1.887 ms/op [Average]
  (min, avg, max) = (4.384, 4.487, 4.591), stdev = 0.103
  CI (99.9%): [2.600, 6.374] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.434 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.627 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.214 ±(99.9%) 0.012 ms/op
Iteration   1: 4.933 ±(99.9%) 0.015 ms/op
Iteration   2: 5.391 ±(99.9%) 0.014 ms/op
Iteration   3: 4.828 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.051 ±(99.9%) 5.463 ms/op [Average]
  (min, avg, max) = (4.828, 5.051, 5.391), stdev = 0.299
  CI (99.9%): [≈ 0, 10.514] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.736 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 5.300 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.952 ±(99.9%) 0.019 ms/op
Iteration   1: 4.587 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.545 ms/op
                 createUser·p0.99:   8.700 ms/op
                 createUser·p0.999:  24.150 ms/op
                 createUser·p0.9999: 26.674 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   2: 4.528 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.382 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  23.245 ms/op
                 createUser·p0.9999: 33.552 ms/op
                 createUser·p1.00:   34.996 ms/op

Iteration   3: 4.435 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.138 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.774 ms/op
                 createUser·p0.999:  21.398 ms/op
                 createUser·p0.9999: 28.567 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 212338
  mean =      4.516 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 152 
    [ 2.500,  5.000) = 171933 
    [ 5.000,  7.500) = 37165 
    [ 7.500, 10.000) = 2203 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     23.036 ms/op
     p(99.9900) =     32.473 ms/op
     p(99.9990) =     34.906 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.354 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.680 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.407 ±(99.9%) 0.012 ms/op
Iteration   1: 4.217 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   4.915 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   7.930 ms/op
                 existUser·p0.999:  14.664 ms/op
                 existUser·p0.9999: 22.984 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 4.277 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.903 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   7.676 ms/op
                 existUser·p0.999:  14.733 ms/op
                 existUser·p0.9999: 30.524 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   3: 4.187 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.987 ms/op
                 existUser·p0.50:   4.039 ms/op
                 existUser·p0.90:   4.841 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  14.389 ms/op
                 existUser·p0.9999: 33.882 ms/op
                 existUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 227101
  mean =      4.227 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 128 
    [ 2.500,  5.000) = 207403 
    [ 5.000,  7.500) = 17332 
    [ 7.500, 10.000) = 1624 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     33.091 ms/op
     p(99.9990) =     35.384 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.454 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.970 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.668 ±(99.9%) 0.015 ms/op
Iteration   1: 4.628 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.489 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  20.805 ms/op
                 getUser·p0.9999: 24.186 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   2: 4.320 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.068 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  12.351 ms/op
                 getUser·p0.9999: 26.450 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   3: 4.604 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.064 ms/op
                 getUser·p0.50:   4.448 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   8.028 ms/op
                 getUser·p0.999:  23.314 ms/op
                 getUser·p0.9999: 27.908 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 212617
  mean =      4.513 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 180463 
    [ 5.000,  7.500) = 28627 
    [ 7.500, 10.000) = 2785 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.064 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     26.736 ms/op
     p(99.9990) =     28.701 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.678 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 5.715 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.524 ±(99.9%) 0.018 ms/op
Iteration   1: 5.162 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   5.915 ms/op
                 listUser·p0.95:   6.562 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  25.701 ms/op
                 listUser·p0.9999: 30.370 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   2: 5.401 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  18.212 ms/op
                 listUser·p0.9999: 22.943 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 5.247 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.695 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 19.500 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 182077
  mean =      5.268 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 87625 
    [ 5.000,  7.500) = 88153 
    [ 7.500, 10.000) = 4808 
    [10.000, 12.500) = 1016 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      6.955 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     29.058 ms/op
     p(99.9990) =     31.364 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.197 ± 3.108  ops/ms
ClientPb.existUser                       thrpt       3   7.721 ± 2.236  ops/ms
ClientPb.getUser                         thrpt       3   7.246 ± 3.180  ops/ms
ClientPb.listUser                        thrpt       3   6.333 ± 0.870  ops/ms
ClientPb.createUser                       avgt       3   4.449 ± 0.734   ms/op
ClientPb.existUser                        avgt       3   4.263 ± 1.672   ms/op
ClientPb.getUser                          avgt       3   4.487 ± 1.887   ms/op
ClientPb.listUser                         avgt       3   5.051 ± 5.463   ms/op
ClientPb.createUser                     sample  212338   4.516 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.087           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.135           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.036           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.473           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.996           ms/op
ClientPb.existUser                      sample  227101   4.227 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.681           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.664           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.586           ms/op
ClientPb.getUser                        sample  212617   4.513 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.064           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.882           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.249           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.118           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.736           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.162           ms/op
ClientPb.listUser                       sample  182077   5.268 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.917           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.226           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.955           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.448           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.058           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.687           ms/op
