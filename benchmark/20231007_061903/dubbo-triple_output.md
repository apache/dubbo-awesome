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
# Warmup Iteration   1: 2.266 ops/ms
# Warmup Iteration   2: 5.929 ops/ms
# Warmup Iteration   3: 8.733 ops/ms
Iteration   1: 9.206 ops/ms
Iteration   2: 9.237 ops/ms
Iteration   3: 9.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.165 ±(99.9%) 1.819 ops/ms [Average]
  (min, avg, max) = (9.051, 9.165, 9.237), stdev = 0.100
  CI (99.9%): [7.346, 10.983] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.084 ops/ms
# Warmup Iteration   2: 8.331 ops/ms
# Warmup Iteration   3: 9.308 ops/ms
Iteration   1: 9.721 ops/ms
Iteration   2: 9.763 ops/ms
Iteration   3: 9.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.700 ±(99.9%) 1.370 ops/ms [Average]
  (min, avg, max) = (9.617, 9.700, 9.763), stdev = 0.075
  CI (99.9%): [8.330, 11.071] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.911 ops/ms
# Warmup Iteration   2: 8.220 ops/ms
# Warmup Iteration   3: 8.964 ops/ms
Iteration   1: 9.207 ops/ms
Iteration   2: 9.301 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.245 ±(99.9%) 0.912 ops/ms [Average]
  (min, avg, max) = (9.207, 9.245, 9.301), stdev = 0.050
  CI (99.9%): [8.333, 10.157] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.988 ops/ms
# Warmup Iteration   2: 7.062 ops/ms
# Warmup Iteration   3: 7.837 ops/ms
Iteration   1: 7.710 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.796 ±(99.9%) 1.376 ops/ms [Average]
  (min, avg, max) = (7.710, 7.796, 7.850), stdev = 0.075
  CI (99.9%): [6.421, 9.172] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.610 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.004 ms/op
Iteration   1: 3.423 ±(99.9%) 0.008 ms/op
Iteration   2: 3.487 ±(99.9%) 0.003 ms/op
Iteration   3: 3.511 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.474 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (3.423, 3.474, 3.511), stdev = 0.046
  CI (99.9%): [2.636, 4.311] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.749 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.005 ms/op
Iteration   1: 3.325 ±(99.9%) 0.006 ms/op
Iteration   2: 3.337 ±(99.9%) 0.004 ms/op
Iteration   3: 3.275 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.312 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.275, 3.312, 3.337), stdev = 0.033
  CI (99.9%): [2.711, 3.913] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.890 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.005 ms/op
Iteration   1: 3.459 ±(99.9%) 0.005 ms/op
Iteration   2: 3.512 ±(99.9%) 0.004 ms/op
Iteration   3: 3.425 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.465 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.425, 3.465, 3.512), stdev = 0.044
  CI (99.9%): [2.668, 4.263] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.698 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.006 ms/op
Iteration   1: 4.171 ±(99.9%) 0.006 ms/op
Iteration   2: 4.148 ±(99.9%) 0.004 ms/op
Iteration   3: 4.166 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.162 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (4.148, 4.162, 4.171), stdev = 0.012
  CI (99.9%): [3.945, 4.379] (assumes normal distribution)


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
# Warmup Iteration   1: 8.301 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.009 ms/op
Iteration   1: 3.412 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  17.214 ms/op
                 createUser·p0.9999: 20.974 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.392 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.470 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 22.938 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280253
  mean =      3.424 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10943 
    [ 2.500,  5.000) = 265089 
    [ 5.000,  7.500) = 3343 
    [ 7.500, 10.000) = 244 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 235 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     22.117 ms/op
     p(99.9990) =     25.546 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.092 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.008 ms/op
Iteration   1: 3.353 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.624 ms/op
                 existUser·p0.999:  20.106 ms/op
                 existUser·p0.9999: 22.870 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   2: 3.478 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  22.092 ms/op
                 existUser·p0.9999: 25.173 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  13.271 ms/op
                 existUser·p0.9999: 26.278 ms/op
                 existUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282620
  mean =      3.395 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8074 
    [ 2.500,  5.000) = 267950 
    [ 5.000,  7.500) = 5498 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     14.791 ms/op
     p(99.9900) =     25.614 ms/op
     p(99.9990) =     26.692 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.146 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.010 ms/op
Iteration   1: 3.545 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  14.174 ms/op
                 getUser·p0.9999: 19.921 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   2: 3.499 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  19.058 ms/op
                 getUser·p0.9999: 21.215 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.443 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  18.431 ms/op
                 getUser·p0.9999: 23.167 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274443
  mean =      3.495 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3820 
    [ 2.500,  5.000) = 264038 
    [ 5.000,  7.500) = 5458 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.870 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.014 ms/op
Iteration   1: 4.131 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  17.256 ms/op
                 listUser·p0.9999: 22.144 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 4.083 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 16.985 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 4.024 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.720 ms/op
                 listUser·p0.999:  16.212 ms/op
                 listUser·p0.9999: 18.352 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235176
  mean =      4.079 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 227061 
    [ 5.000,  7.500) = 6096 
    [ 7.500, 10.000) = 1170 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     23.634 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.165 ± 1.819  ops/ms
ClientPb.existUser                       thrpt       3   9.700 ± 1.370  ops/ms
ClientPb.getUser                         thrpt       3   9.245 ± 0.912  ops/ms
ClientPb.listUser                        thrpt       3   7.796 ± 1.376  ops/ms
ClientPb.createUser                       avgt       3   3.474 ± 0.837   ms/op
ClientPb.existUser                        avgt       3   3.312 ± 0.601   ms/op
ClientPb.getUser                          avgt       3   3.465 ± 0.798   ms/op
ClientPb.listUser                         avgt       3   4.162 ± 0.217   ms/op
ClientPb.createUser                     sample  280253   3.424 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.229           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.793           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.117           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.887           ms/op
ClientPb.existUser                      sample  282620   3.395 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.214           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.186           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.791           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.614           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.329           ms/op
ClientPb.getUser                        sample  274443   3.495 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.053           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.828           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.478           ms/op
ClientPb.listUser                       sample  235176   4.079 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.872           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.496           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.953           ms/op
